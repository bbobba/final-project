Put models under this directory.
import os
from flask import Flask, request, jsonify, render_template

from keras.preprocessing import image