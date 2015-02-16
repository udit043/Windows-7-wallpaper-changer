#include <iostream>
#include <stdio.h>
#include <stdlib.h>
#include <windows.h>
using namespace std;

void Stealth();
void Stealth()
{
  HWND Stealth;
  AllocConsole();
  Stealth = FindWindowA("ConsoleWindowClass", NULL);
  ShowWindow(Stealth,0);
}

int main()
{
  Stealth();  //To hide console window	
  const wchar_t *filenm = "C:\\Users\\Udit Raikwar\\Pictures\\finaldp1.jpg"; //address of your image
  bool isWallSet=SystemParametersInfoW(SPI_SETDESKWALLPAPER, 0,(void*)filenm, SPIF_UPDATEINIFILE);	 
  return 0;
}
