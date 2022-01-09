# Tar Cheat Sheet

## **Compress file atau directory**
- **tar**
```
tar -cvf nama.tar /path/to/directory-atau-file
```

- **gzip**
```
tar -czvf nama.tar.gz /path/to/directory-atau-file
```

- **bzip2**
```
tar -cjvf nama.tar.bz /path/to/directory-atau-file
```

## **Ekstrak Archive**
- **tar**
```
tar -xvf nama.tar

- **gzip**
```
tar -xzvf nama.tar.gz
```

- **bzip2**
```
tar -xjvf nama.tar.bz
```

## **Format Perintah tar**
* -c: Membuat file file tar.
* -x: Mengekstrak file tar.
* -z: Membuat/mengekstrak file dengan program gzip.
* -j: Membuat/mengekstrak file dengan program bzip2.
* -v: Menampilkan progress pembuatan file.
* -f: Menunjuk pada nama file tar.
