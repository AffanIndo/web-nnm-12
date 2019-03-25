# web-nnm-12

Website NNM 12 - Faces of Humanity

## Penjelasan file dan folder:

### Folder

* `./css/` - Berisi file CSS yang sudah dicompile dari SCSS. File di dalam folder ini hanya untuk produksi, developer tidak boleh mengedit file di dalam folder ini.
* `./etc/` - Berisi resource-resource yang dibutuhkan developer, seperti framework, logo-logo, dan gambar-gambar maskot. Folder ini **tidak** untuk diupload ke server. Folder ini **harus** dimasukkan ke dalam `.gitignore`.
* `./img/` - Berisi gambar-gambar yang dibutuhkan.
* `./js/` - Berisi script-script yang dibutuhkan. Kebanyakan berasal dari templatenya sehingga sebaiknya jangan diedit.
* `./mail/` - Berisi script untuk "contact us". Berasal dari templatenya sehingga sebaiknya jangan diedit.
* `./node_modules` - Berisi dependency yang dibutuhkan. Jika tidak ada, maka developer menginstallnya dengan `npm install` di dalam folder project. Folder ini **tidak** untuk diupload ke server. Folder ini **harus** dimasukkan ke dalam `.gitignore`.
* `./scss/` - Berisi file-file styling untuk diedit. Kebanyakan berasal dari templatenya sehingga sebaiknya jangan diedit, kecuali file `_nnm.scss` yang merupakan styling untuk main page. Ada juga `_variables.scss` yang berisi warna-warna yang akan dipakai dalam web.
* `./story/` - Berisi storyline NNM 12.
* `./vendor/` - Berisi dependency untuk website. File ini **harus** dimasukkan ke dalam `.gitignore`.
* `.vimrc` - Settingan untuk text editor Vim. File ini **tidak** untuk diupload ke server. File ini **harus** dimasukkan ke dalam `.gitignore`.
* `.gulpfile.js` - 
* `index.html` - 
* `LICENSE` - 
* `package-lock.json` - Daftar dependency yang dibutuhkan.
* `package.json` - Daftar dependency yang dibutuhkan.
* `README.md` - Dokumentasi project web-nnm-12.
* `README_AGENCY.md` - Dokumentasi project agency, template dasar web-nnm-12.
* `TODO` - Daftar hal-hal yang akan dikerjakan.
