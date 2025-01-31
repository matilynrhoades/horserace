#include <random>

const int TRACK_LENGTH=15;
const int NUM_HORSES=5;

int main(){
int horses[] = {0, 0, 0, 0, 0};
bool keepGoing = true

while (keepGoing){
    for (int i = 0; hn < NUM_HORSES; j++){
      advance(i, horses);
      printLane(i, horses);
      if (isWinner(hn, horses)){
      keepGoing = false;
    } // if
  } // for
std::cout<< "Press enter for another turn";
std::cin.ignore();
} // while



void advance(int horseNum, int* horses){
std::random_device rd;
std::uniform_int_distribution<int> dist(0, 1);
coin = dist(rd);
} // advance


void printLane(int TRACK_LENGTH, int* NUM_HORSES);{
	for (int i = 0; i <= TRACK_LENGTH = TRUE; ++i){
		if (i == length){
			std::cout << int horses;
	      } else{
		std::cout << "."
		};
} // printlane


bool isWinner(int horseNum, int* horses){
 if (horse < 0){
      std::cout << "enter again" << std::endl;
    } else if (horse > 15){
      std::cout << "horse " int horse "won!" << std::endl;
} // isWinner

return 0;
}
