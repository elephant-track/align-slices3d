# Align Slices 3D+t extension

This ImageJ plugin is for applying [2D slice alignment](https://sites.google.com/site/qingzongtseng/template-matching-ij-plugin/tuto2) to all slices in a 3D+t hyperstack.

## Prerequisites

ImageJ/Fiji and [Template Matching and Slice Alignment --- ImageJ Plugins](https://sites.google.com/site/qingzongtseng/template-matching-ij-plugin)

## Install

Copy a plugin file `align_slices3d-1.0.0.jar` to the `plugins/` directory of your ImageJ/Fiji.

## Usage

### 1. Run Align slices

First, prepare a 2D+t stack from your 3D+t hyperstack (e.g. maximum projection, specifying a Z level).

Run Plugins>Template Matching>Align slices in stack... as instructed [here](https://sites.google.com/site/qingzongtseng/template-matching-ij-plugin/tuto2) with the "show align coordinates in results tabl" option.


### 2. Run Align slices

Open the 3D+t hyperstack and run Plugins>Hyperstack Slice Alignment.