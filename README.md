# akshay-samrat-info

Portfolio site (`index.html`, served by GitHub Pages) and resume.

## Rebuild the resume PDF

The PDF is printed from `resume/resume.html` with Microsoft Edge. Edit the HTML, then run in PowerShell from this folder:

```powershell
& "C:\Program Files (x86)\Microsoft\Edge\Application\msedge.exe" --headless --disable-gpu --no-pdf-header-footer --print-to-pdf="$PWD\Akshay_Samrat_Resume.pdf" "file:///$($PWD -replace '\\','/')/resume/resume.html"
```
