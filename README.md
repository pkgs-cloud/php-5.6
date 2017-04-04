# PHP 5.6

RPM packages for RHEL / CentOS 7

### Installation

##### Install PHP 5.6

1. Install [**pkgs.cloud** release repository](https://github.com/pkgs-cloud/release)
2. `yum install php-5.6-release -y`
3. `yum install php -y`

##### List all available packages

```bash
yum --disablerepo="*" --enablerepo="pkgs.cloud-php-5.6" list available
```

### Current build

#### PHP 5.6.30 packages

```
php                        5.6.30
php-bcmath                 5.6.30
php-cli                    5.6.30
php-common                 5.6.30
php-dba                    5.6.30
php-dbg                    5.6.30
php-devel                  5.6.30
php-embedded               5.6.30
php-enchant                5.6.30
php-fpm                    5.6.30
php-gd                     5.6.30
php-gmp                    5.6.30
php-imap                   5.6.30
php-interbase              5.6.30
php-intl                   5.6.30
php-ldap                   5.6.30
php-litespeed              5.6.30
php-mbstring               5.6.30
php-mcrypt                 5.6.30
php-mssql                  5.6.30
php-mysqlnd                5.6.30
php-odbc                   5.6.30
php-opcache                5.6.30
php-pdo                    5.6.30
php-pear                   1.10.3
php-pecl-geoip             1.1.1
php-pecl-igbinary          2.0.1
php-pecl-igbinary-devel    2.0.1
php-pecl-imagick           3.4.3
php-pecl-imagick-devel     3.4.3
php-pecl-jsonc             1.3.10
php-pecl-jsonc-devel       1.3.10
php-pecl-lzf               1.6.5
php-pecl-msgpack           0.5.7
php-pecl-msgpack-devel     0.5.7
php-pecl-redis             3.1.1
php-pecl-ssh2              0.13
php-pecl-uuid              1.0.4
php-pecl-xdebug            2.5.1
php-pecl-zip               1.13.5
php-pgsql                  5.6.30
php-process                5.6.30
php-pspell                 5.6.30
php-recode                 5.6.30
php-snappy                 0.1.6
php-snmp                   5.6.30
php-soap                   5.6.30
php-tidy                   5.6.30
php-xml                    5.6.30
php-xmlrpc                 5.6.30
```

#### Additional packages

```
gd                         2.2.4    
gd-devel                   2.2.4    
gd-progs                   2.2.4    
libzip5                    1.2.0
libzip5-devel              1.2.0
libzip5-tools              1.2.0
openssl                    1.0.2k
openssl-libs               1.0.2k
openssl-devel              1.0.2k 
openssl-perl               1.0.2k 
openssl-static             1.0.2k 
redis                      3.2.8
```

### Help with RPM packages

- [Open an issue](https://github.com/pkgs-cloud/release/issues)

---

##### DISCLAIMER

THIS SOFTWARE IS PROVIDED "AS IS" AND ANY EXPRESSED OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE REGENTS OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION)
HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.