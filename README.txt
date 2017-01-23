# PDF-Highlights

### A CLI tool for extracting highlighted text from PDFs

Run the following commands to install dependencies (using Homebrew package manager on macOS):

    brew install frescobaldi PyQt poppler qt sip pyqt

Next, install Python dependencies:

    pip install unidecode PyQt4 python-poppler-qt4

Let me know if you have trouble installing dependencies on your system: stephen.mclaughlin@utexas.edu

Chmod the script file, replacing the path with your own:

    chmod 755 /path/to/pdf-highlights/highlights

Create the directory '/opt/bin' (if you don't already have one) and copy the Python script `highlights` into it:

    mkdir /opt/bin/
    cp /path/to/pdf-highlights/highlights /opt/bin/

Add the following line to your bashrc file (`/etc/bashrc` on macOS):

    export PATH=$PATH:/opt/bin

Open a new terminal window and run the script like so:

    highlights /path/to/a/PDF_file.pdf

Your highlights will be displayed in the terminal.