# Compress and extract files with tar

Quick reference to extract and compress files with tar and gz, since it seems I can't remember the right options. 
And I'm not [alone](http://xkcd.com/1168/)...

### Compress file

```bash
tar -zcvf file.tar.gz directory-name
```bash
to compress a folder. 


### Extract file

```bash
tar -zxvf file.tar.gz 
```
to extract an entire archive. The -v option stands for verbose, so it can be omitted.