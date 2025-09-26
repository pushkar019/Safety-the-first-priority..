# Safety-the-first-priority..
#include <stdio.h>

int main() {
    int seatBeltStatus;

    printf("Welcome to the Seat Belt Safety System\n");
    printf("Enter seat belt status (0 = Unlocked, 1 = Locked): ");
    scanf("%d", &seatBeltStatus);

    if (seatBeltStatus == 1) {
        printf("Seat belt is locked.\n");
        printf("Car started.\n");
    } else {
        printf("Seat belt is not locked.\n");
        printf("Car will not start. Please fasten the seat belt.\n");
    }

    return 0;
}
