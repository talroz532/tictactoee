#include <stdlib.h>
#include <stdio.h>

char board[3][3]= {'1','2','3','4','5','6','7','8','9'};
int input;
int i;
int j;
char mark;
int count = 0; 

//printing the board
void board1(){
for (i=0;i<3;i++){
    printf("\n\n\n");
for(j=0;j<3;j++){
    printf("\t\t");
    printf(" | %c | ",board[i][j]);
}  
}
    printf("\n");
}

//check win
int checkwin(){

    if (board[0][0]== board[0][1] && board[0][0]== board[0][2]){
printf("\n\t\t %c Is the WINNER!!!\n\n", mark);
return 0;
    }else if(board[1][0]== board[1][1] && board[1][0]== board[1][2]){
printf("\n\t\t %c Is the WINNER!!!\n\n", mark);
return 0;
    }else if(board[2][0]== board[2][1] && board[2][0]== board[2][2]){
printf("\n\t\t %c Is the WINNER!!!\n\n", mark);
return 0;
    }else if(board[0][0]== board[1][0] && board[0][0]== board[2][0]){
printf("\n\t\t %c Is the WINNER!!!\n\n", mark);
return 0;
    }else if(board[0][1]== board[1][1] && board[0][1]== board[2][1]){
printf("\n\t\t %c Is the WINNER!!!\n\n", mark);
return 0;
    }else if(board[0][2]== board[1][2] && board[0][2]== board[2][2]){
printf("\n\t\t %c Is the WINNER!!!\n\n", mark);
return 0;
    }else if (board[0][0]== board[1][1] && board[0][0]== board[2][2]){
printf("\n\t\t %c Is the WINNER!!!\n\n", mark);
return 0;
    }else if (board[0][2]== board[1][1] && board[0][2]== board[2][0]){
printf("\n\t\t %c Is the WINNER!!!\n\n", mark);
return 0;
    }
}


int main(){

printf("\n\n\t\tWelcome to tic tac toee game\n");
 board1();

//loop start
while(1){

//Alternately X/O
if(count % 2 == 0){
    printf("\nX Enter place: ");
    mark= 'X';
}else{
    printf("\nO Enter place: ");
    mark = 'O';
}

//Input + check if it letter

if((scanf("%d", &input) != 1 )|| (input >9 || input<1)){
printf("error\n");
return 0;
}
if(input<=9 && input >=1){  
    for(i=0;i<3;i++){
        for(j=0;j<3;j++){
            board[i][j];
            if(board[i][j]== 'X' || board[i][j]== 'O'){

            }
        }
    }
}else{
    count++;
}

    printf("\n");

//printing  X/O



    if(input==1){
    board[0][0] =mark;   
}else if(input==2){
   board[0][1]=mark;
}else if(input==3){
   board[0][2]=mark;
}else if(input==4){
   board[1][0]=mark;
}else if(input==5){
  board[1][1]=mark;
}else if(input==6){
   board[1][2]=mark;
}else if(input==7){
   board[2][0]=mark;
}else if(input==8){
   board[2][1]=mark;
}else if(input==9){
   board[2][2]=mark;
}

system("clear");
board1();
if(count == 10 || checkwin()==0) break;

   
}
    return 0;
}
