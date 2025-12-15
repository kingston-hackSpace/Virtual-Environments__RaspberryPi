# Virtual Environments__RaspberryPi


A virtual environment on a Raspberry Pi is a safe, separate place for installing Python dependencies for your projects. It avoids installation conflicts with other Python dependancies on your RPi.

Read more [here](https://www.raspberrypi.com/news/using-python-with-virtual-environments-the-magpi-148/)

----
## Create a Virtual Environment (venv) for your project

- Ensure you have venv installed:
  
      sudo apt install python3-venv

- Create a virtual environment in your Desktop:

      python3 -m venv venv

- Activate it:

      source venv/bin/activate


- Install dependencies:

      pip install <package-name>

- Deactivate it:

      deactivate

- Delete an environment

      rm -rf env

