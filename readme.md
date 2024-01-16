# StockSync

## Introduction
StockSync is an inventory management system built in C++.This project has authentication and role based authorization. This helps to manage supplies, stocks, and orders, while ensuring seamless billing processes.

This project was built in third semester for OOP project

## Team Members
* Anil Shrestha
* Ashok Prasad Neupane

## Libraries required for the project
- wxWidget: https://github.com/wxWidgets/wxWidgets
- Bcrypt: https://github.com/pyca/bcrypt

## Compiling instructions
- We recommend compiling with C++ standard 17+
- Visual Studio is the recommended IDE
- Download the Libraries from given links
- Build the codes of libraries for the required OS environment
    - wxWidget
        - Go to directory in the wxWidget library: build > msw > wz_cv17.sln
        - debug and release according to the os platform
        - Go the project, in the view tab, go to other Windows, in property manager > add existing property, add .props file of this library
    
    - Bcrypt
        - Put the Downloaded codes in the project and include the classes just like our custom classes (as it is a small library)
- Put all the codes of our project directories in the root directory and build it in Visual Studio