# automation-using-excel

## Automate encoding

- to create a list to automate encode videos by converting **any audio codec** inside the video to **hev2aac** using CMD
- to reducing the size of the video without losing much of the quality of the video itself
- Example : .mp4 (AVC and AAC-LC) to .mkv (AVC and AAC-LC-SBR-PS/HE-AACv2)
- here excel file to generate list for auto-encoding :

    [encode-nero-ffmpeg-mkv.xlsx](encode-nero-ffmpeg-mkv.xlsx)

1. Install

    You need to install this encoder AND add them to **PATH** :

    - ffmpeg
    - mkvtoolnix
    - neroaacenc

2. How

    open the HELP sheet in the Excel file

3. Documentation

    [mkvmerge documentation](https://mkvtoolnix.download/doc/mkvmerge.html)

    [mkvextract documentation](https://mkvtoolnix.download/doc/mkvextract.html)

    [ffmpeg Documentation](https://ffmpeg.org/ffmpeg.html)

    `neroaacenc -help`

## Automate video chapter file

- to make video chapter file (.xml) automatically

    [video-chapter-file.xlsx](video-chapter-file.xlsx)

> honestly I made these files just to make my life easier, but i try to share it
