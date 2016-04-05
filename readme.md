# Luca Example

#### Dependencies

Conda

##### Linux

Various dev tools required by lucas dependencies:

`sudo apt-get install libtiff5-dev libjpeg8-dev zlib1g-dev libfreetype6-dev 
liblcms2-dev libwebp-dev tcl8.6-dev tk8.6-dev python-tk`

##### Windows

It is not currently possible to run Luca on Windows due to numerous *nix-only
requirements.

#### Setup

```
conda env create
```

##### Usage

* Use Luca to tally financial statement data into tax categories
* Transfer the results of that to form input JSON for Luca
* Use Luca to prepare tax forms from form input JSON

