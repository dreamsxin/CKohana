CKohana
=======

Compile a kohana into an extension.

将kohana转为C扩展，发挥PHP的速度极限。

email:dreamsxin@qq.com

Completed-API:https://github.com/dreamsxin/CKohana/wiki/Completed-API

#### Requirements
We need some packages previously installed.

* PHP 5.x development resources
* GCC compiler

Ubuntu:

```bash
sudo apt-get install php5-dev php5-mysql gcc make
```

Compilation
-----------

```bash
cd CKohana
phpize
./configure --enable-kohana
make
sudo make install 
```

Add extension to your php.ini

```bash
extension=kohana.so
```

Finally restart the webserver
