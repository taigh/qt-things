qt-things
=========

some useful qt classes

VideoRecorder
=========

- Derived from QImage
- Just create, draw on it and call VideoRecorder::frameReady() each time you want to add new frame to stream
- H264
- Container guessed from file name

VideoPlayer
=========

- Derived from QGLWidget
- frame-accurate seeking
- any format supported by ffmpeg
- convenient mouse zooming and panning
- video-space point click signal