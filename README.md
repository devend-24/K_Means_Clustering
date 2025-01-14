# 🖼️ K-Means Image Clustering

This project uses the **K-Means Clustering Algorithm** to simplify images by reducing them to a fixed number of colors, making them visually striking and computationally efficient. In this implementation, the number of colors is set to **5**.

---

## 📜 Features
- 🟢 Cluster colors in any image into **5 representative colors**.
- 🖌️ Output includes both the simplified image and the corresponding color palette.
- 📊 Leverages the **K-Means Clustering Algorithm** for unsupervised learning.
- ⚡ Fast and efficient processing, even for large images.

---


## 🚀 Usage

1. Place the image you want to cluster in the `input_images` folder.
2. Run the script:
   ```bash
   python cluster_image.py --input input_images/your_image.jpg --output output_images/clustered_image.jpg
   ```
   - Replace `your_image.jpg` with the name of your image.
   - The simplified image will be saved in the `output_images` folder.

3. 🎨 View the extracted color palette in the terminal or as an optional image.

---

## 🧠 How It Works
1. **Load Image**: Read the input image and resize it for faster processing.
2. **Flatten Image**: Convert the image into a 2D array of pixels.
3. **K-Means Clustering**: Apply the K-Means algorithm to group pixels into 5 clusters.
4. **Reconstruct Image**: Replace each pixel with the nearest cluster's color.
5. **Save Output**: Save the new image and optionally display the color palette.


---

## ✨ Example 1
![Original Image](https://github.com/user-attachments/assets/484b65b4-aa06-4587-bc3c-643200a40487)


### Simplified Image with 5 Colors
![Simplified_Image](https://github.com/user-attachments/assets/7fdc6426-9135-48ef-9509-2d95a77edc35)


## ✨ Example 2
![Original Image](https://github.com/user-attachments/assets/e15c0039-c27b-4d29-a708-a332603a791e)

![Simplified Image](https://github.com/user-attachments/assets/f069fbdd-c85f-49a7-9f2a-9e8c198137c5)

---

## 🛡️ Requirements
- Python 3.7+
- NumPy
- Matplotlib

---

## 🙌 Acknowledgments
- K-Means implementation inspired by **scikit-learn's clustering module**.
- 
---

## 💡 Future Improvements
- Add support for choosing the number of clusters dynamically.
- Integrate a GUI for easier interaction.
- Optimize performance for high-resolution images.



Happy clustering! 🎉

