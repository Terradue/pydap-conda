About pydap
===========

Home: http://pydap.org/

Package license: MIT

Summary: Pure Python Opendap/DODS client and server

Installing pydap
================

Installing `pydap` from the `terradue` channel can be achieved by adding `terradue` to your channels with:

```
conda config --add channels terradue
```

Once the `terradue` channel has been enabled, `pydap` can be installed with:

```
conda install pydap -c terradue
```

Notes
=====

This package contains a patch to fix the issue described in:

* https://github.com/Unidata/thredds/issues/1144#issuecomment-420107544
* https://www.unidata.ucar.edu/support/help/MailArchives/netcdf/msg14389.html

The patch has been sent upstream https://github.com/pydap/pydap/pull/180
