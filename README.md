public class Main {
    public static void main(String[] args) {

        Book firstBook = new Book();

        firstBook.title = "Dune";
        firstBook.author = "Frank Herbert";
        firstBook.pageCount = 421;
        firstBook.status = "Available";

        System.out.println("This book is " + firstBook.title);
        System.out.println("The author of the book is " + firstBook.author);
        System.out.println("The page count of this is " + firstBook.pageCount);
        System.out.println("The status of this book is " + firstBook.status);
    }
}

