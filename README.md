# STM32-MatrixRGB

### ประกาศใน main function
MatrixRGB_Init(); // MatrixRGB
trick.attach(&Runline, 0.001);    // Update MatrixRGB;

### การต่อใช้งาน (STM32-411RE)
RST(A0);LAT(A1);SLB(A2);SDAA(D7);SCLL(D6);lineRGB(D8,D9,D10,D11,D12,D13,D3,D4);

### font ใช้งานอยู่ใน function unsigned char font8_8[92][8];

### แสดง font ใช้ function : DispChar(char chr,unsigned char R,unsigned char G,unsigned char B);
