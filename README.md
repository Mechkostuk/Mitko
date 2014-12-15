Mitko
=====
#ifndef TySofia_H
#define TySofia_H
#include <stdio.h>
#include <malloc.h>
#include <stdlib.h>
#define MAX 100
#define DATE 3
#define NAME 60
#define ID 10
#define MAKER 40
#define NUM 9
void Create (struct Node *head);
void Enter  (int arr[DATE]);
void Date   (struct Node *head);

struct Node 
{
   float  value;
	unsigned int qnty;
	unsigned int  dtfxp;
	char name ;
	unsigned int ident ;
	char maker;
	int date[DATE];
	char number[NUM];
	char expd[3];
	unsigned int taxnumb ;
	struct Node *next;
	
};

   
#endif
  
