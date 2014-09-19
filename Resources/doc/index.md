# BlendEzMatrixBundle Documentation

Symfony Bundle to work with eZ Matrix in eZ 5.*

## Prerequisites

This bundle requires eZ Publish >5.2 (Enterprise) or >2013.04.0 (Community).

## Installation

### Step 1: Download BlendEzMatrixBundle using composer


``` bash
$ php composer.phar require blend/ez-matrix-bundle 'dev-master'
```


### Step 2: Enable the bundle

Enable the bundle in the kernel:

``` php
<?php
// app/AppKernel.php

public function registerBundles()
{
    $bundles = array(
        // ...
        new Blend\EzMatrixBundle\BlendEzMatrixBundle(),
    );
}
```
