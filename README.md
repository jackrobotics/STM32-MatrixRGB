# STM32-MatrixRGB

### Init main function
- MatrixRGB_Init(); // MatrixRGB
- trick.attach(&Runline, 0.001);    // Update MatrixRGB;

### การต่อใช้งาน (STM32-411RE)
- RST(A0);
- LAT(A1);
- SLB(A2);
- SDAA(D7);
- SCLL(D6);
- lineRGB(D8,D9,D10,D11,D12,D13,D3,D4);

### การสั่งงานแต่ละ dot
dots[Row][Column][RGB];

//[8]:Row:8 row in LED plane
//[8]:Column:8 column in one row
//[3]:Color:RGB data: 0 for Red; 1 for green, 2 for Blue
