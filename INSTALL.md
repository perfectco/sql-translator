## OSX

Here is how I installed this on OSX.

* `cpan install inc::Module::Install Module::Install::ReadmeFromPod Module::Install::AuthorTests Package::Variant YAML JSON`
  * I said yes to all the defaults as I hadn't already setup cpan
  * `source ~/.bashrc` after if you hadn't already setup cpan
* `perl Makefile.PL`
* `make install`

