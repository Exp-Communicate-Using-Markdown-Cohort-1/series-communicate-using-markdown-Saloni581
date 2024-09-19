# Hello! I am learning markdown. 
## This is very helpful while collaborating on github. Markdown extension is .md or simply .markdown (the full name).

![Bhagwat Gita](https://github.com/user-attachments/assets/7a980269-ecdc-4c4d-bda9-1a7a7e26a6e2)


```
// BhagavadGitaVerse.java

class BhagavadGitaVerse {
    private String chapter;
    private int verseNumber;
    private String verseText;
    private String translation;

    // Constructor to initialize the verse details
    public BhagavadGitaVerse(String chapter, int verseNumber, String verseText, String translation) {
        this.chapter = chapter;
        this.verseNumber = verseNumber;
        this.verseText = verseText;
        this.translation = translation;
    }

    // Method to display the verse
    public void displayVerse() {
        System.out.println("Chapter: " + chapter);
        System.out.println("Verse " + verseNumber + ": " + verseText);
        System.out.println("Translation: " + translation);
    }
}

public class Main {
    public static void main(String[] args) {
        // Creating an object representing a specific verse
        BhagavadGitaVerse verse = new BhagavadGitaVerse(
            "Chapter 2 - Sankhya Yoga",
            47,
            "कर्मण्येवाधिकारस्ते मा फलेषु कदाचन। मा कर्मफलहेतुर्भूर्मा ते संगोऽस्त्वकर्मणि॥",
            "You have the right to perform your prescribed duties, but you are not entitled to the fruits of your actions. Never consider yourself to be the cause of the results of your activities, nor be attached to inaction."
        );

        // Displaying the verse
        verse.displayVerse();
    }
}

```
