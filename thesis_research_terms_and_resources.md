## Research Terms

### Scoping

**Scoping** means exploring what already exists in your topic area.

* You search papers, datasets, and ideas
* Understand what others have done
* Identify gaps (what’s missing)

Think of it as:
> What has already been researched, and where can I contribute?

### Literature Review

A **literature review** is a structured summary of existing research.

* You analyze multiple papers
* Compare methods and results
* Show where your work fits

This is usually the **first major section** of a research paper.

### Research Gap

The **research gap** is the problem that hasn’t been solved yet.

* Missing accuracy?
* No dataset for your case?
* Existing method is slow?

Your project should **solve or improve this gap**.

### Methodology

This explains **how you solve the problem**.

* Algorithms used (OpenCV, ML models)
* Steps of your system
* Tools and datasets

This is the **core technical part** of your paper.

## Publishing Terms

### Q1–Q4 (Journal Ranking)

Q1–Q4 are **quartile rankings** of journals based on their impact and quality.

* **Q1** → Top 25% (highest quality)
* **Q2** → 25–50%
* **Q3** → 50–75%
* **Q4** → Lowest 25%

[Read this to learn more about it](https://mdmasumbillah.vercel.app/blogs/cmj385zqu0005jl04jhtjgain)

These rankings are usually based on databases like [Scopus](https://www.scopus.com/).
  - Platforms like Scopus store:
    - Thousands of journals
    - Millions of research papers
    - Citation data (who cites whom)
  - They look at things like:
    - How many times papers are cited
    - How influential the journal is
    - Quality and consistency of publications


**Example:**
A computer vision journal published by IEEE and indexed in Scopus may be ranked as Q1.

**How to check/generate it:**
* Go to [SCImago Journal Rank](https://www.scimagojr.com/)
* Search journal name → see quartile (Q1–Q4)

**How to Use This as a Beginner**

1. Problem identification:
   - Start with Q1 papers to see the most credible gaps.
   - Focus on their “Introduction” and “Related Work” sections.
2. Methodology development:
   - Q2 papers often have detailed methods and experiments.
   - Good for adapting methods to your own project.
3. Experimentation / benchmarking:
   - Q3 papers may give datasets, results, or open-source code.
   - Useful when building your model or testing.
4. Learning / small-scale projects:
   - Q4 papers are simpler, easy to replicate.
   - Great for practice or understanding concepts.

### Journal

A **journal** is a place where research papers are published regularly.

* More detailed and strict
* Takes longer to publish
* Higher credibility

**Example:**
[IEEE Access](https://ieeeaccess.ieee.org/)

**How to publish:**
1. Choose a journal related to your topic  
2. Format your paper using their template  
3. Submit via their submission system  
4. Paper goes through peer review  

### Conference

A **conference** is an event where researchers present papers.

* Faster publication
* You may present your work
* Good for beginners

**Example:**
[IEEE ICCV (International Conference on Computer Vision)](https://iccv2023.thecvf.com/)

**How to publish:**
1. Find a conference (IEEE, Springer, etc.)  
2. Submit paper before deadline  
3. If accepted → present your work  

### Indexing

**Indexing** means a journal/conference is listed in trusted databases.

* Shows quality and credibility
* Important for your CV

Common indexes:

* [Scopus](https://www.scopus.com/)
* [Web of Science](https://www.webofscience.com/)

### DOI (Digital Object Identifier)

A unique link/ID for a research paper.

Like a permanent URL for your paper.

**Example:**
https://doi.org/10.1109/5.771073

**How to get it:**
* Automatically assigned when your paper is published  
* Provided by publisher (IEEE, Springer, Elsevier)

## Research Skills

### Citation

Giving credit to other papers.

**Common citation styles:**
* IEEE  
* APA  
* MLA 

**Tools:**

* [Zotero](https://www.zotero.org/)  
* [Mendeley](https://www.mendeley.com/)  

**How to use:**
1. Import research papers (PDFs) into the tool  
2. Organize them into folders  
3. Use plugin (Word/Google Docs) to insert citations automatically  
4. Generate bibliography instantly  

### Plagiarism

Copying others’ work without credit

* Always paraphrase and cite
* Use plagiarism checkers

### Peer Review

Your paper is checked by experts before publication.

### Simple Workflow for You

1. Scoping (read papers)
2. Find research gap
3. Choose dataset
4. Build solution (OpenCV)
5. Evaluate results
6. Write paper
7. Submit to conference/journal


## General Dataset Repositories

These are great starting points with lots of categories:

* [**Mendeley Data**](https://data.mendeley.com/)  
  Open-access research datasets (including computer vision and medical imaging).

* [**IEEE DataPort**](https://ieee-dataport.org/)  
  Engineering and AI datasets, including computer vision.

* [**ICPSR**](https://www.icpsr.umich.edu/)  
  Social science datasets (less useful for computer vision).

* [**Kaggle**](https://www.kaggle.com/datasets)  
  Huge collection of datasets (images, videos, annotations). Also includes competitions and notebooks.

* [**UCI Machine Learning Repository**](https://archive.ics.uci.edu/)  
  Classic datasets (not all are vision-focused, but some are useful).

* [**Google Dataset Search**](https://datasetsearch.research.google.com/)  
  Search engine specifically for datasets across the web.

* [**AWS Open Data Registry**](https://registry.opendata.aws/)  
  Large-scale datasets hosted on AWS.

### Image Datasets

Useful for classification, detection, segmentation:

* [**COCO Dataset**](https://cocodataset.org/)  
  One of the most popular datasets for object detection and segmentation.

* [**ImageNet**](https://www.image-net.org/)  
  Massive dataset for image classification tasks.

* [**Open Images Dataset**](https://storage.googleapis.com/openimages/web/index.html)  
  Millions of annotated images with bounding boxes.

* [**MNIST**](http://yann.lecun.com/exdb/mnist/)  
  Simple dataset for beginners (digit recognition).

* [**CIFAR-10**](https://www.cs.toronto.edu/~kriz/cifar.html)  
  Small images for quick experiments.

### Video Datasets

For tracking, motion detection, activity recognition:

* [**UCF101**](https://www.crcv.ucf.edu/data/UCF101.php)  
  Human action videos (e.g., running, jumping).

* [**HMDB51**](https://serre-lab.clps.brown.edu/resource/hmdb-a-large-human-motion-database/)  
  Another popular dataset for human actions.

* [**KITTI Dataset**](http://www.cvlibs.net/datasets/kitti/)  
  Great for object detection, tracking, and depth estimation.

### Face & Human Datasets

For face recognition, emotion detection, pose estimation:

* [**LFW Dataset**](http://vis-www.cs.umass.edu/lfw/)  
  Face recognition benchmark dataset.

* [**CelebA**](https://mmlab.ie.cuhk.edu.hk/projects/CelebA.html)  
  Annotated face dataset with attributes (smiling, glasses, etc.).

* [**MPII Human Pose Dataset**](http://human-pose.mpi-inf.mpg.de/)  
  Human pose estimation data.

### Specialized Datasets

Depending on your project niche:

* [**Cityscapes Dataset**](https://www.cityscapes-dataset.com/)  
  Street scenes for semantic segmentation.

* [**Pascal VOC**](http://host.robots.ox.ac.uk/pascal/VOC/)  
  Classic dataset for detection and segmentation.

### Tools to Create Your Own Dataset

Sometimes the best dataset is your own:

* [**LabelImg**](https://github.com/tzutalin/labelImg)  
  For bounding box labeling.

* [**CVAT**](https://cvat.org/)  
  Advanced annotation for images/videos.

* [**Roboflow**](https://roboflow.com/)  
  Helps you collect, label, and augment datasets.