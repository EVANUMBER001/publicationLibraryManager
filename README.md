Publication Project
This project simulates a publication library with books and magazines. It utilizes Java classes, inheritance, and the Comparable interface to organize and display publications based on their genre and title.

Classes and Enum
Genre Enum
The Genre enum represents different genres of publications, such as SCIENCE, ROMANCE, COMIC, CLASSIC, ATHLETIC, BEAUTY, FASHION, ENTERTAINMENT, and THRILLER.

Publication Class
The Publication class is an abstract class implementing the Comparable interface. It represents a generic publication and has properties:

title: Title of the publication.
genre: Genre of the publication (from the Genre enum).
edition: Edition number.
year: Publication year.
It includes methods to print information, print a footer, get the type, and get the author or publisher.

Book Class
The Book class extends Publication and represents a book. It has an additional property:

author: Author of the book.
Magazine Class
The Magazine class extends Publication and represents a magazine. It has an additional property:

publisher: Publisher of the magazine.
Running the Project
The PublicationProject class is the main class that demonstrates the functionality of the publication library. It creates a list of Publication objects (including both books and magazines), sorts them based on genre and title, and prints out the information.

To run the project, execute the main method in the PublicationProject class.

Sample Output
The program will display the publications sorted by genre and title, including information such as title, edition, publication year, type (book or magazine), and author or publisher.

Bad Blood: Secrets and Lies in a Silicon Valley Startup. Edition (1) published in 2018 thriller by John Carreyrou. All rights reserved!
The Hundred-Page Machine Learning Book. Edition (1) published in 2019 science by Andriy Burkov. All rights reserved!
People. Edition (466) published in 2020 entertainment by Meredith Corporation. All rights reserved!
Sports Illustrated. Edition (633) published in 2020 athletic by Meredith Corporation. All rights reserved!
