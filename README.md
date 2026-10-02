#include <stdio.h>

// ประกาศและนิยามฟังก์ชัน void inputAndShow()
void inputAndShow() {
    int math, physics, chemistry;

    // รับค่าคะแนนทั้ง 3 วิชา
    printf(”Enter Math score: “);
    scanf(”%d“, &math);
    printf(”Enter Physics score: “);
    scanf(”%d“, &physics);
    printf(”Enter Chemistry score: “);
    scanf(”%d“, &chemistry);

    // แสดงผลคะแนนทันทีภายในฟังก์ชัน
    printf(”\n-- Score Summary —\n“);
    printf(”Math: %d\n“, math);
    printf(”Physics: %d\n“, physics);
    printf(”Chemistry: %d\n“, chemistry);
}

int main() {
    // เรียกใช้งานฟังก์ชันจาก main()
    inputAndShow();

    return 0;
}
