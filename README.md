jdk7-howto-build
================

```

  git clone https://github.com/openjdk/jdk7
  cd jdk7
  git clone https://github.com/openjdk/jdk7-corba corba
  git clone https://github.com/openjdk/jdk7-jaxp  jaxp
  git clone https://github.com/openjdk/jdk7-jaxws jaxws
  git clone https://github.com/openjdk/jdk7-hotspot hotspot
  git clone https://github.com/openjdk/jdk7-jdk     jdk
  git clone https://github.com/openjdk/jdk7-langtools langtools

  Set the environment variable ALT_BOOTDIR to the location of JDK 6.

  make sanity
  make all

```
