# KeyLogger : An Information Gathering Software!

Keylogger written in Python with features including taking screenshots, recording microphone, gather clipboard contents, and getting system information

An advanced keylogger has been created in python which has the capability of sending emails, getting screenshots, recording your microphone, getting computer information, and the clipboard. All features work together to create both a keylogger and a spyware-like payload.


#To add an email functionality, we will be using the email module.
Modules to install:

from email.mime.multipart
import MIMEMultipart
from email.mime.text
import MIMEText from email.mime.base
import MIMEBase
from email import encoders
import smtplib



To record with microphone, used the sounddevice module and writing to a .wav file using the scipy.io.wavefile module.


To take a screenshot,used the ImageGrab from the Pillow Module.
