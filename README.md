
![STEMROLLER](https://github.com/user-attachments/assets/89393fcc-5282-4927-8699-b7868568c76e)

# stemroller-linuxbuild

This repository contains the Linux build files for StemRoller, an application that allows you to isolate vocals, drums, bass, and other instrumental stems from any song with a single click. Due to GitHub's file size limitations, large files have been moved to external storage.

## Download the Builds

The application builds are available for download from the following links:

- [dist folder on Mega](https://mega.nz/folder/MjxR3LjI#ayf_jR_XzG5JmlEQ73811w)
- [squashfs-root folder on Mega](https://mega.nz/folder/tjA03Ibb#I73Qo-nus6Vp05LDw6Z5eg)
- [anyos-extra-files folder on Mega](https://mega.nz/folder/N2RWlKIT#vkxEnFRVTcQPkUS2z8m8IA)

## How to Use

1. Download the necessary files from the links above.
2. Follow the instructions in the README to set up and run StemRoller on your Linux system.

For more information about StemRoller, visit the [official repository](https://github.com/stemrollerapp/stemroller).


# StemRoller

StemRoller is the first free app which enables you to separate vocal and instrumental stems from any song with a single click! StemRoller uses Facebook's state-of-the-art [Demucs](https://github.com/facebookresearch/demucs) algorithm for demixing songs and integrates search results from YouTube.

Simply type the name/artist of any song into the search bar and click the **Split** button that appears in the results! You'll need to wait several minutes for splitting to complete. Once stems have been extracted, you'll see an **Open** button next to the song - click that to access your stems!

_We also have a [Discord server](https://www.stemroller.com/chat) with update announcements and support_.

## Quick Start

Using StemRoller couldn't be easier - just head to the [StemRoller website](https://stemroller.com) or the [releases page](https://github.com/stemrollerapp/stemroller/releases) and download the latest version! That bundle includes everything you need to split stems. If, however, you want to get involved in StemRoller development, read on...

### Linux 

Install `nodejs` `npm` `ffmpeg` `demucs` and `electron` globally using your preferred package manager. 

```
sudo apt install nodejs npm ffmpeg
pip install demucs
npm install -g electron
```

## Clone the repository and install the development dependencies:

```
git clone https://github.com/stemrollerapp/stemroller.git
cd stemroller
npm i -D
```

## Run in Development Mode

`npm run dev`

## Run in Production Mode

`npm run build:svelte && npm run start`

## Production Build

### Linux

`npm run build:linux`

## License

Your choice of Public Domain (Unlicense) or MIT No Attribution - please read the [LICENSE](https://github.com/stemrollerapp/stemroller/blob/main/LICENSE) file for more information.
