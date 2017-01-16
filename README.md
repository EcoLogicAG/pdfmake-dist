#Update

Clone https://github.com/bpampuch/pdfmake

Build from source

    git clone https://github.com/bpampuch/pdfmake.git
    cd pdfmake
    npm install # or: yarn
    git submodule update --init  libs/FileSaver.js
    npm run build # or: yarn run build

Add vfs_fonts.js to the end of pdfmake.min.js and copy over to this build directory - done