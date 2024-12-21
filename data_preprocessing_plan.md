# Data Preprocessing Plan

## Goals
- Organize videos into folders by gloss.
- Ensure consistent naming conventions for files.
- Perform basic cleaning or trimming if required.

## Tasks
1. **Create Folder Structure**
   - Organize videos under `Occ#_Group#` > `Glosses` > `Gloss_memberID.mp4`.

2. **File Naming Convention**
   - Format: `Gloss_Occ#_Group#_MemberID.mp4`

3. **Video Trimming and Cleaning**
   - Use OpenCV or ffmpeg to standardize video formats.

4. **Upload to Cloud**
   - Store the preprocessed videos on a cloud drive for team access.

## Tools
- Python with `os` module for folder organization.
- OpenCV or ffmpeg for video processing.
- Google Drive for cloud storage.
