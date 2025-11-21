# CV LaTeX Files - Instructions for Overleaf

## Files Included

1. **Masood_Nazari_CV_ATS.tex** - **RECOMMENDED** - ATS-friendly, simple formatting
2. **Masood_Nazari_CV.tex** - ModernCV style (more visually appealing but less ATS-friendly)

## Quick Start in Overleaf

### Option 1: ATS-Friendly Version (Recommended for Job Applications)

1. Go to [Overleaf.com](https://www.overleaf.com) and create a free account
2. Click "New Project" → "Blank Project"
3. Delete the default `main.tex` file
4. Upload `Masood_Nazari_CV_ATS.tex` or copy-paste its contents
5. Rename it to `main.tex` (or keep the original name)
6. Click "Recompile" to generate the PDF

### Option 2: ModernCV Version (For Networking/Portfolio)

1. In Overleaf, create a new project
2. Upload `Masood_Nazari_CV.tex`
3. You may need to add the moderncv package:
   - Go to "Menu" → "Compiler" → Select "pdfLaTeX"
   - The moderncv package should be automatically available in Overleaf

## Customization

### To Update Contact Information:
- Edit the `\cvheader` section in the ATS version
- Edit the personal data section in the ModernCV version

### To Add/Remove Sections:
- Simply add or remove `\section{}` blocks
- Maintain bullet points using `\begin{itemize}` format

### To Change Formatting:
- **ATS Version**: Modify margins in `\usepackage[margin=0.75in]{geometry}`
- **ModernCV Version**: Change `\moderncvstyle{classic}` to `banking`, `casual`, or `oldstyle`

## UK Market Optimizations Applied

✅ British English spelling (e.g., "optimisation", "visualisation")
✅ UK date format (DD/MM/YYYY implied in date ranges)
✅ UK phone number format (+44)
✅ UK currency (£)
✅ UK-specific terminology (e.g., "VAT" instead of "sales tax")

## ATS-Friendly Features

✅ Simple, clean formatting
✅ Standard section headings
✅ Keyword-rich content
✅ No complex tables or graphics
✅ Standard fonts
✅ Proper spacing and margins
✅ Text-based (no images that ATS can't read)

## Tips for Using in Overleaf

1. **Compilation**: Use pdfLaTeX compiler (default)
2. **Sharing**: Use "Share" button to get a shareable link
3. **Download**: Click "PDF" button to download
4. **Version Control**: Overleaf has built-in version history
5. **Collaboration**: Share with recruiters/career advisors for feedback

## Troubleshooting

- **Missing packages**: Overleaf usually has all common packages pre-installed
- **Compilation errors**: Check for special characters (use `\&` instead of `&`, `\%` instead of `%`)
- **Formatting issues**: Ensure you're using the correct compiler (pdfLaTeX)

## Next Steps

1. Upload to Overleaf and compile
2. Review the PDF output
3. Make any final customizations
4. Download as PDF
5. Test with ATS systems (e.g., upload to job boards to check parsing)

## File Structure

```
Masood_Nazari_CV_ATS.tex    - ATS-friendly version (RECOMMENDED)
Masood_Nazari_CV.tex        - ModernCV styled version
CV_README.md                - This file
```

