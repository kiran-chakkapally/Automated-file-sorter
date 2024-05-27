# Automatic File Sorter

## Introduction
I created this project because it was taking a lot of time for me to organize my files into folders, which is always a repetitive task. This script automates the file organization process, saving time and ensuring that files are neatly arranged in their respective directories. Automating such tasks not only increases efficiency but also minimizes the chances of errors that can occur when sorting files manually. Additionally, this project is a great example of how simple scripts can significantly improve daily workflows.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Requirements](#requirements)
- [How It Works](#how-it-works)
  - [Import Required Modules](#import-required-modules)
  - [Define the Path](#define-the-path)
  - [List All Files in the Directory](#list-all-files-in-the-directory)
  - [Define Folder Names](#define-folder-names)
  - [Create Folders if They Don't Exist](#create-folders-if-they-dont-exist)
  - [Move Files to Their Respective Folders](#move-files-to-their-respective-folders)

## Overview
The "Automatic File Sorter" is a Python script designed to organize files in a specified directory by moving them into subfolders based on their file extensions. This project demonstrates basic file handling and directory management using Python's `os` and `shutil` modules.

## Features
- Automatically sorts files into folders based on file type.
- Supports common file types: CSV, text, and image files.
- Can be easily extended to support additional file types.
- Increases efficiency by reducing the time spent on manual file organization.
- Minimizes errors associated with manual sorting.

## Requirements
- Python 

## How It Works

### Import Required Modules
- `os`: Interacts with the operating system, handling file paths and directories.
- `shutil`: Performs high-level operations on files, such as copying and moving.

### Define the Path
- Specifies the directory containing the files to be sorted.

### List All Files in the Directory
- Gathers a list of all files in the specified directory.

### Define Folder Names
- Lists folder names where files will be moved based on their extensions (e.g., CSV files, Text files, Image files).

### Create Folders if They Don't Exist
- Checks if each folder exists in the specified path and creates them if they don't.

### Move Files to Their Respective Folders
- Iterates over each file and moves it to the corresponding folder based on its extension (e.g., `.csv`, `.png`, `.txt`).

