# Read Working In a Professional Environment > base64 Images

today we worked independently and finished features/squashed bugs

## What is a Base64 Encoded Image?

encoding is how the format data is stored, base64 encoding turn the image into html text so it's part of the html file itself.

## What are the drawbacks of using Base64 Encoding?

Browsers and CDN's can't cache the images because they are part of the html file and can't be accessed by a normal url link. Servers must process the images to encode them.

## Why are these drawbacks issues in this day and age versus in the past?

because we can't cache the images, it increases bandwith use and processing time, file size is increased most of the time as well. Base64 is an outdated tool used for the early days of the internet. using seperate images will bring a much better user experinece as well.