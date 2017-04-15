# VIT-CaptchaParser
Parses the captcha in vit website by using brute force algorithm


Code is embedded in a function,CaptchaParse. Call the function with the bmp captcha image in VIT website as an argument.


"""
img=Image.open("yourimagefilename")
captcha=CaptchaParse(img)
"""




captcha will have the resolved captcha as a string
