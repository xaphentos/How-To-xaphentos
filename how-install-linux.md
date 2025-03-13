## How to install linux on your computer

## 1. Introduction
This guide will teach you how to install linux on your computer step by step.


## 2.Pre-Installation Steps

First of all, before installing system you need to make sure that you follow these few steps:

**select distribution**: Linux have a lot of different versions, but for begginers i would like to recommend to install something easy like Ubuntu or Linux Mint.
**system requriments**: For comfortable use, you will need a 2-core CPU, at least 1.5GB of RAM, and at least 15GB of Hard drive.
**download ISO**: Go to the official Linux distribution website and download the ISO image of your chosen distro (e.g., [Ubuntu Downloads](https://ubuntu.com/download)).
**download rufus**: use rufus to write your image on your usb flash, you will need at least 4GB usb drive (all data on usb flash will be deleated)

## 3. Boot from USB:

1. Restart your computer (Go to start > power button > restart) and enter BIOS/UEFI (by pressing F2 / F12 / Del / ESC)
2. select your usb in boot menu.
3.  select install in grub

## 4. Open installer (on ubuntu), select time-zone, language,disk.
![Ubuntu Community Image](https://ubuntucommunity.s3.us-east-2.amazonaws.com/original/3X/3/a/3a7fffa914037195d7242fc7edce07242756186f.jpeg)

## 5. After installation is complete restart your computer and go to BIOS/UEFI, change your hard drive on top and remove usb flash / formate it later.

## 6. After Installing Systems you can install additional drives (if need) 

## 7. Update packages by command:
sudo apt update && sudo apt upgrade
