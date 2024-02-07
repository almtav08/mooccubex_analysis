# How to run the experiments

1. The first thing you need to do is downloand the MOOCCubeX Dataset from [https://github.com/THU-KEG/MOOCCubeX](https://github.com/THU-KEG/MOOCCubeX). You only need to download the following files (follow the MOOCCubeX instructions to download the required files):
   - `video_id-ccid.txt`
   - `video.json`
   - `user-video.json`
   - `user.json`
   - `course.json`
   - `concept.json`
   - `concept-video.txt`
2. While the data is downloading, you can install the dependencies by running the following command:
   ```pip install -r requirements.txt```
3. Once the files are downloaded you need to run the Import and Initialize the data cells to prepare all necesary data for the tests.
4. After this process is finished, you can run the `Data Analysys` cells to perform an analysis of the data itself. These cells corresponds to the correspondent perspectives described in the proposed work.
5. Once the data analysis is completed you can run the `Translations` and analyze the desired topics in more detail. Two options for the default translator are given. Please feel free to use the one that best suits your needs. The translations are stored in the corresponding `.pkl` file.

---

If you have any questions you can contact me at: [alemarti@uji.es](mailto:alemarti@uji.es)

---

This experiment was developed by Alex Martínez-Martínez as part of his research in the Institute of New Imaging Technologies at the Universitat Jaume I.

---

Coauthors: Raul Montoliu and Inmaculada Remolar.

---