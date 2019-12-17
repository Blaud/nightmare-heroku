web: export DISPLAY=':99.0'
web: Xvfb :99 -screen 0 1024x768x24 > /dev/null 2>&1 &
web: DEBUG=* xvfb-run --auto-servernum --server-args="-screen 0 1024x768x24" node --harmony index.js
