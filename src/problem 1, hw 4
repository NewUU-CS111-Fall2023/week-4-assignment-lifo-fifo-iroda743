problem 1
#include <iostream>
#include <vector>

void bubbleSort(std::vector<std::string>& titles) {
    int n = titles.size();
    
    for (int i = 0; i < n - 1; ++i) {
        for (int j = 0; j < n - i - 1; ++j) {
            if (titles[j] > titles[j + 1]) {
                std::string temp = titles[j];
                titles[j] = titles[j + 1];
                titles[j + 1] = temp;
            }
        }
    }
}

int main() {
    std::vector<std::string> bookTitles = {
        "Catcher in the Rye",
        "Pride and Prejudice",
        "To Kill a Mockingbird",
        "The Great Gatsby",
        "Moby Dick"
    };

    // The list of book titles
    bubbleSort(bookTitles);

    std::cout << "Sorted list of book titles:\n";
    for (const std::string& title : bookTitles) {
        std::cout << title << "\n";
    }

    return 0;
}
