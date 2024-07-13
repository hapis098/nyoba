
## Penjelasan code

'''
import cv2
import numpy as np
import matplotlib.pyplot as plt

# Memuat gambar
gambar = cv2.imread('jeruk.jpg')
gambar_rgb = cv2.cvtColor(gambar, cv2.COLOR_BGR2RGB)

