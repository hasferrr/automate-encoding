# automate-encoding

- to create a list to automate encode videos by converting **any audio codec** inside the video to **hev2aac** using CMD
- to reducing the size of the video without losing much of the quality of the video itself
- Example : .mp4 (AVC and AAC-LC) to .mkv (AVC and AAC-LC-SBR-PS/HE-AACv2)
- here excel file to generate list for auto-encoding :

    [Excel File](encode-nero-ffmpeg-mkv.xlsx)

## Install

You need to install this encoder AND add them to **PATH** :

- ffmpeg
- mkvtoolnix
- neroaacenc

## How

open the HELP sheet in the Excel file

## Documentation

[mkvmerge documentation](https://mkvtoolnix.download/doc/mkvmerge.html)

[mkvextract documentation](https://mkvtoolnix.download/doc/mkvextract.html)

[ffmpeg Documentation](https://ffmpeg.org/ffmpeg.html)

`neroaacenc -help`

