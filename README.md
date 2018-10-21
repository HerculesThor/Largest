# Largest

//this is the code
#include <iostream>
#define SIZE 10

using namespace std;

int largestInArray(int myArray[], int arraySize);

int main(){
    int i, n, largest, myArray[10];
     cout << "Enter the size of the array : ";
    cin >> n;
    cout << "Enter the elements of the array : ";
    for (i = 0; i < n; i++){
        cin >> myArray[i];
    }

    // Get the largest element in the array
    largest = largestInArray(int myArray, SIZE);

    // if your functions works well this should print out 100, which is the largest in the array above
    cout << largest;
    return 0;
}

int largestInArray(int myArray[], int arraySize){
    int largest ,i ,n;

     largest = myArray[0];
    for (i = 0; i < n; i++)
    {
        if (largest < myArray[i])
            largest = myArray[i];
    }
    return largest;

}
