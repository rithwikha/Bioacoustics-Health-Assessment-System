================================================================================
  BIOACOUSTIC ECOSYSTEM HEALTH ASSESSMENT PLATFORM
  Final Project Submission Package
================================================================================

  Team:        Ajay Mekala, Rithwikha Bairagoni, Srivalli Kadali
  Institution: Montclair State University
  Course:      Research Methods in Computing
  Date:        April 2026
  Version:     2.0

--------------------------------------------------------------------------------

PACKAGE CONTENTS

  01_Source_Code/
      The runnable source code of the application. All files needed to
      deploy the platform locally or on Streamlit Cloud.

        app.py                       Main Streamlit application (2,623 lines)
        requirements.txt             Python package dependencies
        packages.txt                 OS packages for Streamlit Cloud
        README.md                    Repository readme
        .devcontainer/
          devcontainer.json          GitHub Codespaces configuration

  02_Project_Report/
      The primary academic deliverable (45 pages). Contains the formal
      project report with certificate, declaration, abstract, literature
      survey, SRS, UML/DFD/ER diagrams, implementation details, testing,
      results, and IEEE references. This is the main document for
      evaluators and examiners.

        BioAcoustic_Platform_Project_Report.docx
        BioAcoustic_Platform_Project_Report.pdf

  03_Project_Manual/
      Professional technical reference manual (49 pages). Documents all
      27 features, deployment procedures, configuration, troubleshooting,
      and developer guidance. Complements the Report with
      implementation-level detail.

        BioAcoustic_Platform_Project_Manual.docx
        BioAcoustic_Platform_Project_Manual.pdf

  04_Source_Code_Listing/
      Syntax-highlighted source code document (55 pages). The complete
      source of the application rendered in print-ready form with line
      numbers and color-coded syntax. Suitable as a submission appendix.

        BioAcoustic_Platform_Source_Code.docx
        BioAcoustic_Platform_Source_Code.pdf

  05_Presentation/
      Final project presentation (23 slides). Dark forest-tech theme with
      infographic-style layouts, designed for the project defense.

        Bioacoustic_Platform_Presentation.pptx
        Bioacoustic_Platform_Presentation.pdf

--------------------------------------------------------------------------------

RECOMMENDED READING ORDER

  For evaluators:
    1. Start with 02_Project_Report (academic framing, methodology, results)
    2. Reference 03_Project_Manual for specific technical questions
    3. Consult 04_Source_Code_Listing for code-level review
    4. View 05_Presentation for the condensed overview

  For developers who want to run the platform:
    1. Open 01_Source_Code/README.md
    2. Follow the installation steps
    3. Refer to 03_Project_Manual Section 15 (Deployment Guide)

--------------------------------------------------------------------------------

LIVE APPLICATION

  The application is deployed and accessible at:
    https://github.com/mekala27-45/bioacoustic-platform

  Follow the Streamlit Cloud deployment link from the repository readme.

--------------------------------------------------------------------------------

QUICK START (LOCAL INSTALLATION)

  1. Install Python 3.10 or later

  2. From the 01_Source_Code/ directory, run:

       pip install -r requirements.txt

  3. Install FFmpeg for MP3/M4A support:

       Windows:    winget install Gyan.FFmpeg
       macOS:      brew install ffmpeg
       Linux:      sudo apt install ffmpeg libsndfile1

  4. Launch the application:

       streamlit run app.py

  5. Open http://localhost:8501 in any modern browser.

--------------------------------------------------------------------------------

BEFORE FIRST OPENING .docx FILES IN MICROSOFT WORD

  Each Word document contains an auto-generated Table of Contents that
  populates only when Word processes the document. After opening any .docx
  file, navigate to the Table of Contents page, right-click on the TOC
  area, and select "Update Field" to populate the page numbers.

  The .pdf versions included in this package already have the TOC
  populated and are ready to view or print.

--------------------------------------------------------------------------------

SIGNING THE REPORT

  The Project Report (02_Project_Report) contains a Certificate page and
  a Declaration page with signature lines. Before final submission:

    1. Print these two pages from the .docx file
    2. Have the Project Guide and Head of Department sign the Certificate
    3. All three team members sign the Declaration
    4. Scan or photograph the signed pages and either insert them back
       into the document or submit as supplementary pages

--------------------------------------------------------------------------------

FILE SIZE SUMMARY

  File                                                    Size
  --------------------------------------------------------------------
  01_Source_Code/app.py                                   112.9 KB
  01_Source_Code/requirements.txt                           0.2 KB
  01_Source_Code/packages.txt                               0.0 KB
  01_Source_Code/README.md                                  7.4 KB
  01_Source_Code/.devcontainer/devcontainer.json            1.0 KB
  02_Project_Report/BioAcoustic_Platform_Project_Report.docx     51.2 KB
  02_Project_Report/BioAcoustic_Platform_Project_Report.pdf    775.3 KB
  03_Project_Manual/BioAcoustic_Platform_Project_Manual.docx     53.5 KB
  03_Project_Manual/BioAcoustic_Platform_Project_Manual.pdf    742.9 KB
  04_Source_Code_Listing/BioAcoustic_Platform_Source_Code.docx    146.1 KB
  04_Source_Code_Listing/BioAcoustic_Platform_Source_Code.pdf  1.14 MB
  05_Presentation/Bioacoustic_Platform_Presentation.pptx  1.19 MB
  05_Presentation/Bioacoustic_Platform_Presentation.pdf  1.22 MB

  Total package size: 5.40 MB

--------------------------------------------------------------------------------

  Generated on: 2026-04-21 12:09:21

================================================================================
