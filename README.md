## Basic Hadoop commandline.
* In this exercise we will create max-temp.txt file and move this file into hadoop filesystem. We also try to change the permission of max-temp in hadoop file system.

---

### Create file

* Create max-temp file using **touch**

<img src="./imgs/touch.png" alt="Drawing" style="height: 500px;"/>

---

### Python script to write information file.

* Create python script to generate random date and temprature, and write this numbers in max-temp.txt.


<table>
    <tr>
        <td><img src="./imgs/python_gen.png" alt="Drawing" style="height: 500px;" align="middle"/></td>
        <td><img src="./imgs/cat.png" alt="Drawing" style="width: 500px;" align="middle"/></td>
    </tr>
</table>

---

### Move file to Hadoop File System.

* Move max-temp.txt file in to HDFS using **put** command.

<img src="./imgs/put.png" alt="Drawing" style="height: 500px;"/>

---

### Change Permission of file.

* Change the permission of max-temp.txt file using **chmod** command.

<img src="./imgs/chmod.png" alt="Drawing" style="height: 500px;"/>

---
