from rembg import remove
from PIL import Image

input_img = '1.jpg'
output_img = 'rembg-1.png'

input = Image.open(input_img)
output = remove(input)
output.save(output_img)
