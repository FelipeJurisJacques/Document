FROM texlive/texlive:latest
WORKDIR /workspace
RUN tlmgr install latexmk
CMD ["latexmk", "-pdf", "document.tex"]