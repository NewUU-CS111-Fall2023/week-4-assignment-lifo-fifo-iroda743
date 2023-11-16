problem 5
#include <iostream>

void displayColors(const char matrix[][10], int rows, int cols) {
    for (int i = 0; i < rows; ++i) {
        for (int j = 0; j < cols; ++j) {
            char symbol = matrix[i][j];
            switch (symbol) {
                case 'b':
                    std::cout << "\033[1;34m\u25A0\033[0m ";  // Blue
                    break;
                case 'y':
                    std::cout << "\033[1;33m\u25A0\033[0m ";  // Yellow
                    break;
                case 'w':
                    std::cout << "\033[1;37m\u25A0\033[0m ";  // White
                    break;
                default:
                    std::cout << symbol << " ";  // For any other symbol
            }
        }
        std::cout << "\n";
    }
}

int main() {
    //  input matrix
    const char matrix[][10] = {
        {'b', 'b', 'w', 'b', 'b', 'y', 'w', 'w', 'w'},
        {'b', 'b', 'w', 'w', 'b', 'y', 'y', 'b', 'b'},
        {'y', 'y', 'y', 'w', 'w', 'b', 'b', 'b', 'b'},
        {'y', 'e', 'y', 'e', 'y', 'w', 'w', 'b', 'b'},
        {'w', 'b', 'b', 'w', 'w', 'b', 'w', 'w', 'w'},
        {'B', 'b', 'w', 'w', 'w', 'w', 'w', 'y', 'w'}  
    };

    int rows = sizeof(matrix) / sizeof(matrix[0]);
    int cols = sizeof(matrix[0]) / sizeof(matrix[0][0]);

    displayColors(matrix, rows, cols);

    return 0;
}
