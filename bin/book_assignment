import 'dart:math';
class Book{
  String title;
  String author;
  int publicationYear;
  int pagesRead =0;
  static int totalBooks =0;
Book(this.title, this.author, this.publicationYear)
  {
    totalBooks++;
    print('A new book ${this.title} published by ${this.author}');

  }
void read(int pages)
  {
    pagesRead += pages;
    print('You have read $pages pages of ${this.title} book.');

  }
  int getPagesRead() => pagesRead;
String getTitle() => title;
String getAuthor() => author;
 int getPublicationYear() => publicationYear;
 int getBookAge()
  {
    final currentYear = DateTime.now().year;
    return max(0, currentYear - publicationYear);

  }
  String toString ()
  {
  return 'Title: ${this.title} \n Author: ${this.author} \n Publication Year: ${this.publicationYear} \n Pages Read: ${this.pagesRead} \n Age: ${this.getBookAge()}';
  }




}
