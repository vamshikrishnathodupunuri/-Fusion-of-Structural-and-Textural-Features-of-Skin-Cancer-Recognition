• Collected skin image data: A dataset of skin images for both normal skin and skin affected by cancer was collected.
• The collected images were preprocessed to remove any unwanted noise, blur, or other distortions. This step involved converting the images to grayscale, filtering out noise using median filters, and resizing the images to a standard size.
• The skin lesion area was segmented from the normal skin using a thresholding technique. This was done using Otsu thresholding, which separated the image into foreground and background pixels.
• Features were extracted from the segmented images. This included color, texture, and shape features.
• The extracted features were used to train a classifier to differentiate between normal skin and skin affected by cancer. The SVM algorithm was used to train the classifier.
• Finally, the system was tested using a separate set of skin images to evaluate its accuracy in identifying skin cancer. The accuracy of the system was calculated using performance metrics such as precision, recall, and F1 score.
