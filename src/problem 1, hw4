problem 2
#include <iostream>
#include <vector>

void selectionSort(std::vector<int>& denominations) {
    int n = denominations.size();

    for (int i = 0; i < n - 1; ++i) {
        int minIndex = i;
        for (int j = i + 1; j < n; ++j) {
            if (denominations[j] < denominations[minIndex]) {
                minIndex = j;
            }
        }

        std::swap(denominations[i], denominations[minIndex]);
    }
}

int main() {
    //  coins and banknotes
    std::vector<int> denominations = {8, 3, 12, 6, 1};

    selectionSort(denominations);
    std::cout << "Sorted list of denominations:\n";
    for (const int& denomination : denominations) {
        std::cout << denomination << "\n";
    }

    return 0;
}
