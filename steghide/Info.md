
# Steghide

- sudo apt update
- sudo apt install steghide -y
- steghide embed -cf food.jpg -ef secret.txt
- steghide extract -sf food.jpg
- steghide info image.jpg
