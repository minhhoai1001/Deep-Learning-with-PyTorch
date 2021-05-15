# Deep Learning with PyTorch
**ELI STEVENS, LUCA ANTIGA,**
**AND THOMAS VIEHMANN**


## about this book

This book has the aim of providing the foundations of deep learning with PyTorch and showing them in action in a reallife project. We strive to provide the key concepts underlying deep learning and show how PyTorch puts them in the hands of practitioners. In the book, we try to provide intuition that will support further exploration, and in doing so we selectively delve into details to show what is going on behind the curtain. 

*Deep Learning with PyTorch* doesn’t try to be a reference book; rather, it’s a conceptual companion that will allow you to independently explore more advanced material online. As such, we focus on a subset of the features offered by PyTorch. The most notable absence is recurrent neural networks, but the same is true for other parts of the PyTorch API.

## Who should read this book
This book is meant for developers who are or aim to become deep learning practitioners and who want to get acquainted with PyTorch. We imagine our typical reader to be a computer scientist, data scientist, or software engineer, or an undergraduateor later student in a related program. Since we don’t assume prior knowledge of deep learning, some parts in the first half of the book may be a repetition of concepts that are already known to experienced practitioners. For those readers, we hope the exposition will provide a slightly different angle to known topics. We expect readers to have basic knowledge of imperative and object-oriented programming. Since the book uses Python, you should be familiar with the syntax and operating environment. Knowing how to install Python packages and run scripts on your platform of choice is a prerequisite. Readers coming from C++, Java, JavaScript, Ruby, or other such languages should have an easy time picking it up but will need to do some catch-up outside this book. Similarly, being familiar with NumPy will be useful, if not strictly required. We also expect familiarity with some basic linear algebra, such as knowing what matrices and vectors are and what a dot product is.

## How this book is organized: A roadmap
*Deep Learning with PyTorch* is organized in three distinct parts. Part 1 covers the foundations, while part 2 walks you through an end-to-end project, building on the basic concepts introduced in part 1 and adding more advanced ones. The short part 3 rounds off the book with a tour of what PyTorch offers for deployment. You will likely notice different voices and graphical styles among the parts. Although the book is a result of endless hours of collaborative planning, discussion, and editing, the act of writing and authoring graphics was split among the parts: Luca was primarily in charge of part 1 and Eli of part 2 When Thomas came along, he tried to blend the style in part 3 and various sections here and there with the writing in parts 1 and 2. Rather than finding a minimum common denominator, we decided to preserve the original voices that characterized the parts.

Following is a breakdown of each part into chapters and a brief description of each.

**PART 1**

In part 1, we take our first steps with PyTorch, building the fundamental skills needed to understand PyTorch projects out there in the wild as well as starting to build our own. We’ll cover the PyTorch API and some behind-the-scenes features that make PyTorch the library it is, and work on training an initial classification model. By the end of part 1, we’ll be ready to tackle a real-world project.

**PART 2**

In part 2, each chapter moves us closer to a comprehensive solution to automatic detection of lung cancer. We’ll use this difficult problem as motivation to demonstrate the real-world approaches needed to solve large-scale problems like cancer screening. It is a large project with a focus on clean engineering, troubleshooting, and problem
solving.

**PART 3** 

Part 3 is a single chapter on deployment. Chapter 15 provides an overview of how to deploy PyTorch models to a simple web service, embed them in a C++ program, or bring them to a mobile phone.

## About the code
All of the code in this book was written for Python 3.6 or later. The code for the book
is available for download from Manning’s [website](www.manning.com/books/deep-learning-with-pytorch) and on [GitHub](https://github.com/deep-learning-withpytorch/dlwpt-code). Version 3.6.8 was current at the time of writing and is what we used to test the examples in this book.

## Hardware and software requirements
Part 1 has been designed to not require any particular computing resources. Any recent computer or online computing resource will be adequate. Similarly, no certain operating system is required. In part 2, we anticipate that completing a full training run for the more advanced examples will require a **CUDA-capable GPU**. The default parameters used in part 2 assume a GPU with 8 GB of RAM (we suggest an **NVIDIA GTX 1070** or better), but the parameters can be adjusted if your hardware has less RAM available. The raw data needed for part 2’s cancer-detection project is about 60 GB to download, and you will need a total of **200 GB** (at minimum) of free disk space on the system that will be used for training. Luckily, online computing services recently started offering GPU time for free. We discuss computing requirements in more detail in the appropriate sections.

## liveBook discussion forum
Purchase of Deep Learning with PyTorch includes free access to a private web forum run by Manning Publications where you can make comments about the book, ask technical questions, and receive help from the authors and from other users. To access the [forum](https://livebook.manning.com/#!/bookdeep-learning-with-pytorch/)
discussion. You can learn more about Manning’s forums and the [rules of conduct](https://livebook.manning.com/#!/discussion). Manning’s commitment to our readers is to provide a venue where a meaningful dialogue between individual readers and between readers and the author can take place. It is not a commitment to any specific amount of participation on the part of the authors, whose contribution to the forum remains voluntary (and unpaid). We suggest you try asking them some challenging questions lest their interest stray! The forum and the archives of previous discussions will be accessible from the publisher’s website as long as the book is in print.