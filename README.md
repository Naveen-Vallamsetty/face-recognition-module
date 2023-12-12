# face-recognition-module
Embarking on the development of a "Face Recognition Attendance System" during the final year project journey, the initial hurdle encountered was the installation of the face recognition module in Python. This documentation highlights the challenges faced during installation and the successful resolution of those issues.

**Summary of my expreiance**

Installation Steps and Errors:

**Attempt 1**: Installing Face Recognition Module
**Command**: pip install face_recognition
**Error**: Missing dependency libraries - cmake and dlib.
**Resolution 1**: Installing CMake
**Command**: pip install cmake
Successful installation of cmake.

**Attempt 2**: Retry Installing Face Recognition Module
**Command**: pip install face_recognition
**Error**: Dependency library 'dlib' still missing.

**Attempt 3**: Installing Dlib
**Command**: pip install dlib
**Error**: Unsuccessful installation.

**Attempt 4**: Installing Specific Dlib Version
**Command**: pip install dlib==19.24.2
**Error**: Persistence of installation issues.

**Solution**: Manual Installation of Dlib Wheel File
Downloaded the Dlib wheel file from GitHub based on Python version.
Checked Python version using python --version.
Downloaded Dlib wheel file from GitHub.
Command: **pip install dlib-19.22.99-cp310-cp310-win_amd64.whl**
