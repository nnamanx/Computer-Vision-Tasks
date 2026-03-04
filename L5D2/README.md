## Task:

•Get a text image with a white background (you can write it too)
•Manually put some salt (white dots on bold letters) and pepper (black dots on background) noises.
•Use morphology to remove the noise.


## Explanation:
First, make the image pure black and white using threshold so the letters and background are clear. Then we remove small black dots on the white background by keeping only big connected parts (that keeps the letters). After that, we fill small white dots inside the letters using closing, so the text becomes solid and clean. In the end, the image has clean black letters on a white background.
