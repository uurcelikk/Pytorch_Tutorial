# Pytorch_Tutorial
Pytorch Notes in Machine Learning and Deep Learning

This repository provides a Python-based example of working with DICOM files, which are commonly used in the medical imaging field. DICOM (Digital Imaging and Communications in Medicine) files store images and related information, such as patient data and imaging parameters. This example demonstrates how to read, manipulate, and analyze DICOM files using Python.
Digital Imaging and Communications in Medicine (DICOM) is the standard for the communication and management of medical imaging information and related data. (https://www.dicomstandard.org/about)

DICOM used for store and share medical images (or another data). And standardised file format allows the communication between medical devices. Most medical image data in hospitals are stored in this particular file format.

"Accessing DICOM **header** information:
You can access the dicom tags by using the hexadecimal encoded identifiers at the start of each line.
As an example, if you want to get the shape of the image you can use those two identifiers

* (0028, 0010) Rows
* (0028, 0011) Columns
* (0018, 0015) Body Part Examined

The 0x in front of the identifier tells the python interpreter that it should interpret this value as hexadecimal."
***Jose Portilla's Note**

