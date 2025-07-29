---
Instances - Book Chapter
---

The files found here were used in the computational experiments for the Book Chapter.

In total, there are five instances with 1,000 different **customers (addresses)**, taken from the [Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce) database, where each **customer** has their respective order, with the products to be delivered. In addition, we have the stocks of the **fulfilment centers** for each available product, 20 in total.

The information contained in the **Samples.zip** file is detailed below. For all the folders listed, each file corresponds to a different instance.

**Folders:**

- Addresses:
    - The contents of the files are explained as follows:
        - Each row refers to a **customer**.
        - First column refers to the **latitude** of the address of provided **customer**.
        - Second column refers to the **longitude** of the address of provided **customer**.
        - The third column refers to the customer's specific **service center**, if **scenarios 1 and 2** are used to run the instance, as explained in the book chapter.
        - The fourth column indicates whether the specific customer is at the intersection of the two **service centers**, if scenario 2 is used to execute the instance. If the customer is at the intersection, the cell will have the value “**Limbo”**; if the customer is not part of the intersection, the cell will have the value “**No”**.
- Stock:
    - The contents of the files are explained as follows:
        - Each row corresponds to a **fulfilment center**, where the matrix indicates the quantity of items for each product, given by the position (index) of the matrix, available at the indicated **fulfilment center**.
- Orders:
    - The contents of the files are explained as follows:
        - Each line corresponds to a **customer**, where the matrix indicates the quantity of items for each product, given by the position (index) of the matrix, requested in the order of the indicated customer.
- Weights:
    - Orders:
        - Each line corresponds to the volume of the customer's order indicated.
    - Products:
        - Each line corresponds to the volume of the product indicated.
        

Author and Developer: Maria Luíza Teixeira Santos ([marialuizats@usp.br](mailto:marialuizats@usp.br)).

Springer Book: Theory, Algorithms and Experiments in Applied Optimization - Chapter 15.
