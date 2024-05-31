# Python Virtual Environment Manager v1.0

![Application Screenshot](https://github.com/mohabhui/lang_python/blob/main/_gui_images/python_virtual_environment_manager_v1.0.png?raw=true)

## Overview
The Python Virtual Environment Manager v1.0 allows you to easily create, activate, deactivate, delete, and manage Python virtual environments. Follow the instructions below to use the application effectively.

## Functions of Each Button

1. **Create Virtual Environment:**
   - **Python path:** Enter the path to your Python executable (e.g., `C:\py3\python.exe`).
   - **New virtual env dir:** Specify the directory where the new virtual environment will be created (e.g., `C:\venvX`).
   - **Button:** Click "Create virtual env" to create a new virtual environment with the specified settings.

2. **Activate Virtual Environment:**
   - **Select existing virtual env:** Choose an existing virtual environment from the list.
   - **Button:** Click "Activate virtual env" to activate the selected environment.

3. **Deactivate Virtual Environment:**
   - **Button:** Click "Deactivate virtual env" to deactivate the currently active virtual environment.

4. **Delete Virtual Environment:**
   - **Select existing virtual env:** Choose an existing virtual environment from the list.
   - **Button:** Click "Delete virtual env" to delete the selected environment.

5. **Show Available Python Versions:**
   - **Button:** Click "Show available python versions" to display a list of available Python versions on your system.

6. **Show Virtual Environments:**
   - **Button:** Click "Show virtual envs" to display a list of all virtual environments managed by the application.

7. **Show Active Virtual Environment:**
   - **Button:** Click "Show active virtual env" to display the currently active virtual environment.

8. **Check Package in Active Virtual Environment:**
   - **Package in active virtual env:** Enter the name of the package you want to check (e.g., `numpy`).
   - **Button:** Click "Check Package in active virtual env" to find out the location of the specified package within the active virtual environment.

9. **Open Command Prompt for Active Virtual Environment:**
   - **Button:** Click "Open Command Prompt for active virtual env" to open a command prompt window with the active virtual environment activated.

## Additional Information
- **Python Path:** Ensure that the path to your Python executable is valid and correct.
- **Environment List:** The list of environments will be updated automatically when you create, delete, or change environments.
- **Configuration File:** The application uses a configuration file (`settings.json`) to store settings and environment information. This file is automatically updated with changes you make.

## Closing the Application
- **Close:** When you close the application, it will automatically save the current configuration.

Enjoy managing your Python virtual environments with ease!
