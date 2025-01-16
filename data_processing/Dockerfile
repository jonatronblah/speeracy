FROM jitesoft/tesseract-ocr as tessbase
# USER root
COPY ./images/IMG_0002.jpg /tmp/images/IMG_0002.jpg
COPY eng.traineddata equ.traineddata osd.traineddata /usr/local/share/tessdata/

# RUN train-lang eng --best

# RUN tesseract /tmp/images/IMG_0002.jpg stdout