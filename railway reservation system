# Railway-reservation-system-Railway-reservation-system.cbp 

@@ -0,0 +1,52 @@
<?xml version="1.0" encoding="UTF-8" standalone="yes" ?>
<CodeBlocks_project_file>
	<FileVersion major="1" minor="6" />
	<Project>
		<Option title="Railway reservation system" />
		<Option pch_mode="2" />
		<Option compiler="gcc" />
		<Build>
			<Target title="Debug">
				<Option output="bin/Debug/Railway reservation system" prefix_auto="1" extension_auto="1" />
				<Option object_output="obj/Debug/" />
				<Option type="1" />
				<Option compiler="gcc" />
				<Compiler>
					<Add option="-g" />
				</Compiler>
			</Target>
			<Target title="Release">
				<Option output="bin/Release/Railway reservation system" prefix_auto="1" extension_auto="1" />
				<Option object_output="obj/Release/" />
				<Option type="1" />
				<Option compiler="gcc" />
				<Compiler>
					<Add option="-O2" />
				</Compiler>
				<Linker>
					<Add option="-s" />
				</Linker>
			</Target>
		</Build>
		<Compiler>
			<Add option="-Wall" />
		</Compiler>
		<Unit filename="conio.c">
			<Option compilerVar="CC" />
		</Unit>
		<Unit filename="conio2.h" />
		<Unit filename="main.c">
			<Option compilerVar="CC" />
		</Unit>
		<Unit filename="rlyres.c">
			<Option compilerVar="CC" />
		</Unit>
		<Unit filename="rlyres.h" />
		<Extensions>
			<code_completion />
			<envvars />
			<debugger />
			<lib_finder disable_auto="1" />
		</Extensions>
	</Project>
</CodeBlocks_project_file>
 79  
Railway reservation system/Railway reservation system.depend
@@ -0,0 +1,79 @@
# depslib dependency file v1.0
1524913378 source:d:\c.projet\railway reservation system\conio.c
	<stdio.h>
	<stdlib.h>
	<windows.h>
	<string.h>
	"conio2.h"

1524913378 d:\c.projet\railway reservation system\conio2.h
	<conio.h>
	<windows.h>

1525417168 source:d:\c.projet\railway reservation system\main.c
	<stdio.h>
	<stdlib.h>
	"rlyres.h"
	"conio2.h"

1525415169 d:\c.projet\railway reservation system\rlyres.h

1525508464 source:d:\c.projet\railway reservation system\rlyres.c
	<stdio.h>
	"conio2.h"
	"rlyres.h"

1524913380 source:d:\railway reservation system\conio.c
	<stdio.h>
	<stdlib.h>
	<windows.h>
	<string.h>
	"conio2.h"

1524913380 d:\railway reservation system\conio2.h
	<conio.h>
	<windows.h>

1526020373 source:d:\railway reservation system\main.c
	<stdio.h>
	<stdlib.h>
	"rlyres.h"
	"conio2.h"

1525530354 d:\railway reservation system\rlyres.h

1526021760 source:d:\railway reservation system\rlyres.c
	<stdio.h>
	"conio2.h"
	"rlyres.h"
	<stdlib.h>
	<windows.h>

1524913380 source:d:\myproject\railway reservation system\conio.c
	<stdio.h>
	<stdlib.h>
	<windows.h>
	<string.h>
	"conio2.h"

1524913380 d:\myproject\railway reservation system\conio2.h
	<conio.h>
	<windows.h>

1530875865 source:d:\myproject\railway reservation system\main.c
	<stdio.h>
	<stdlib.h>
	"rlyres.h"
	"conio2.h"

1528343687 d:\myproject\railway reservation system\rlyres.h

1530876364 source:d:\myproject\railway reservation system\rlyres.c
	<stdio.h>
	"conio2.h"
	"rlyres.h"
	<stdlib.h>
	<windows.h>
	<string.h>
	<ctype.h>

 30  
Railway reservation system/Railway reservation system.layout
@@ -0,0 +1,30 @@
<?xml version="1.0" encoding="UTF-8" standalone="yes" ?>
<CodeBlocks_layout_file>
	<FileVersion major="1" minor="0" />
	<ActiveTarget name="Debug" />
	<File name="conio2.h" open="1" top="0" tabpos="4" split="0" active="1" splitpos="0" zoom_1="0" zoom_2="0">
		<Cursor>
			<Cursor1 position="0" topLine="317" />
		</Cursor>
	</File>
	<File name="main.c" open="1" top="0" tabpos="1" split="0" active="1" splitpos="0" zoom_1="-1" zoom_2="0">
		<Cursor>
			<Cursor1 position="1226" topLine="0" />
		</Cursor>
	</File>
	<File name="rlyres.c" open="1" top="0" tabpos="2" split="0" active="1" splitpos="0" zoom_1="-1" zoom_2="0">
		<Cursor>
			<Cursor1 position="1146" topLine="798" />
		</Cursor>
	</File>
	<File name="conio.c" open="1" top="0" tabpos="5" split="0" active="1" splitpos="0" zoom_1="0" zoom_2="0">
		<Cursor>
			<Cursor1 position="0" topLine="306" />
		</Cursor>
	</File>
	<File name="rlyres.h" open="1" top="1" tabpos="3" split="0" active="1" splitpos="0" zoom_1="0" zoom_2="0">
		<Cursor>
			<Cursor1 position="93" topLine="0" />
		</Cursor>
	</File>
</CodeBlocks_layout_file>
 BIN +63.4 KB 
Railway reservation system/bin/Debug/Railway reservation system.exe
Binary file not shown.
 419  
Railway reservation system/conio.c
Large diffs are not rendered by default.

 356  
Railway reservation system/conio2.h
@@ -0,0 +1,356 @@
/** @file conio2.h
 * A conio implementation for Mingw/Dev-C++.
 *
 * Written by:
 * Hongli Lai <hongli@telekabel.nl>
 * tkorrovi <tkorrovi@altavista.net> on 2002/02/26.
 * Andrew Westcott <ajwestco@users.sourceforge.net>
 * Michal Molhanec <michal@molhanec.net>
 *
 * Offered for use in the public domain without any warranty.
 */

#ifndef _CONIO2_H_
#define _CONIO2_H_

#include <conio.h>
#ifdef UNICODE
    #include <windows.h>    // we need wchar_t
#endif

#ifdef __cplusplus
extern "C" {
#endif

/**
 * Colors which you can use in your application.
 */
typedef enum
{
    BLACK,          /**< black color */
    BLUE,           /**< blue color */
    GREEN,          /**< green color */
    CYAN,           /**< cyan color */
    RED,            /**< red color */
    MAGENTA,        /**< magenta color */
    BROWN,          /**< brown color */
    LIGHTGRAY,      /**< light gray color */
    DARKGRAY,       /**< dark gray color */
    LIGHTBLUE,      /**< light blue color */
    LIGHTGREEN,     /**< light green color */
    LIGHTCYAN,      /**< light cyan color */
    LIGHTRED,       /**< light red color */
    LIGHTMAGENTA,   /**< light magenta color */
    YELLOW,         /**< yellow color */
    WHITE           /**< white color */
} COLORS;

/*@{*/
/**
 * This defines enables you to use all MinGW conio.h functions without
 * underscore.
 */
#define cgets   _cgets
#define cprintf _cprintf
#define cputs   _cputs
#define cscanf  _cscanf

#ifdef UNICODE
    #define cgetws   _cgetws
    #define getwch   _getwch
    #define getwche  _getwche
    #define putwch   _putwch
    #define ungetwch _ungetwch
    #define cputws   _cputws
    #define cwprintf _cwprintf
    #define cwscanf  _cwscanf
#endif
/*@}*/

/**
 * Define alias for _conio_gettext.
 * If you want to use gettext function from some other library
 * (e.g. GNU gettext) you have to define _CONIO_NO_GETTEXT_ so you won't get
 * name conflict.
 */
#ifndef _CONIO_NO_GETTEXT_
  #define gettext _conio_gettext
#endif

#define ScreenClear clrscr

/**
 * @anchor cursortypes
 * @name Cursor types
 * Predefined cursor types. */
/*@{*/
#define _NOCURSOR 0         /**< no cursor */
#define _SOLIDCURSOR 100    /**< cursor filling whole cell */
#define _NORMALCURSOR 20    /**< cursor filling 20 percent of cell height */
/*@}*/

/**
 * Structure holding information about screen.
 * @see gettextinfo
 * @see inittextinfo
 */
struct text_info {
    unsigned char curx;          /**< cursor coordinate x */
    unsigned char cury;          /**< cursor coordinate y */
    unsigned short attribute;    /**< current text attribute */
    unsigned short normattr;     /**< original value of text attribute after
                                      start of the application. If you don't
                                      called the <TT>inittextinfo</TT> on the
                                      beginning of the application, this always
                                      will be black background and light gray
                                      foreground */
    unsigned char screenwidth;   /**< screen width */
    unsigned char screenheight;  /**< screen height */
};

/**
 * Structure used by gettext/puttext.
 * @see _conio_gettext
 * @see puttext
 */
struct char_info {
#ifdef UNICODE
    wchar_t letter;        /**< character value */
#else
    char letter;           /**< character value */
#endif
    unsigned short attr;   /**< attribute value */
};

/**
 * Returns information of the screen.
 * @see text_info
 */
void gettextinfo (struct text_info * info);

/**
 * Call this if you need real value of normattr attribute in the text_info
 * structure.
 * @see text_info
 */
void inittextinfo (void);

/**
 * Clears rest of the line from cursor position to the end of line without
 * moving the cursor.
 */
void clreol (void);

/**
 * Clears whole screen.
 */
void clrscr (void);

/**
 * Delete the current line (line on which is cursor) and then moves all lines
 * below one line up. Lines below the line are moved one line up.
 */
void delline (void);

/**
 * Insert blank line at the cursor position.
 * Original content of the line and content of lines below moves one line down.
 * The last line is deleted.
 */
void insline (void);

/**
 * Gets text from the screen. If you haven't defined <TT>_CONIO_NO_GETTEXT_</TT>
 * prior to including <TT>conio2.h</TT> you can use this function also under
 * the <TT>gettext</TT> name.
 * @see char_info
 * @see puttext
 * @param left Left coordinate of the rectangle, inclusive, starting from 1.
 * @param top Top coordinate of the rectangle, inclusive, starting from 1.
 * @param right Right coordinate of the rectangle, inclusive, starting from 1.
 * @param bottom Bottom coordinate of the rectangle, inclusive, starting from 1.
 * @param buf You have to pass buffer of size
 * <TT>(right - left + 1) * (bottom - top + 1) * sizeof(char_info)</TT>.
 */
void _conio_gettext (int left, int top, int right, int bottom,
                     struct char_info * buf);

/**
 * Puts text back to the screen.
 * @see char_info
 * @see _conio_gettext
 * @param left Left coordinate of the rectangle, inclusive, starting from 1.
 * @param top Top coordinate of the rectangle, inclusive, starting from 1.
 * @param right Right coordinate of the rectangle, inclusive, starting from 1.
 * @param bottom Bottom coordinate of the rectangle, inclusive, starting from 1.
 * @param buf You have to pass buffer of size
 * <TT>(right - left + 1) * (bottom - top + 1) * sizeof(char_info)</TT>.
 */
void puttext (int left, int top, int right, int bottom, struct char_info * buf);

/**
 * Copies text.
 * @param left Left coordinate of the rectangle, inclusive, starting from 1.
 * @param top Top coordinate of the rectangle, inclusive, starting from 1.
 * @param right Right coordinate of the rectangle, inclusive, starting from 1.
 * @param bottom Bottom coordinate of the rectangle, inclusive, starting from 1.
 * @param destleft Left coordinate of the destination rectangle.
 * @param desttop Top coordinate of the destination rectangle.
 */
void movetext (int left, int top, int right, int bottom, int destleft,
              int desttop);

/**
 * Moves cursor to the specified position.
 * @param x horizontal position
 * @param y vertical position
 */
void gotoxy(int x, int y);

/**
 * Puts string at the specified position.
 * @param x horizontal position
 * @param y vertical position
 * @param str string
 */
void cputsxy (int x, int y, char * str);

/**
 * Puts char at the specified position.
 * @param x horizontal position
 * @param y vertical position
 * @param ch char
 */
void putchxy (int x, int y, char ch);

/**
 * Sets the cursor type.
 * @see @ref cursortypes
 * @param type cursor type, under Win32 it is height of the cursor in percents
 */
void _setcursortype (int type);

/**
 * Sets attribute of text.
 * @param _attr new text attribute
 */
void textattr (int _attr);

/**
 * Sets text attribute back to value it had after program start.
 * It uses text_info's normattr value.
 * @see text_info
 */
void normvideo (void);

/**
 * Sets text background color.
 * @see COLORS
 * @param color new background color
 */
void textbackground (int color);

/**
 * Sets text foreground color.
 * @see COLORS
 * @param color new foreground color
 */
void textcolor (int color);

/**
 * Reads the cursor X position.
 * @returns cursor X position
 */
int wherex (void);

/**
 * Reads the cursor Y position.
 * @returns cursor Y position
 */
int wherey (void);

/**
 * Reads password. This function behaves like cgets.
 *
 * @see cgets
 * @param prompt prompt which will be displayed to user
 * @param str string for the password. <TT>str[0]</TT> have to contain
 * length of the <TT>str</TT> - 3
 * @returns <TT>&str[2]</TT>, the password will be stored in <TT>str</TT>
 * beginning at <TT>str[2]</TT>, in <TT>str[1]</TT> will be length of the
 * string without <TT>\\0</TT>, at <TT>str[2 + str[1]]</TT> will be \\0.
 */
char * getpass (const char * prompt, char * str);

/**
 * Makes foreground colors light.
 * If the current foreground color is less than <TT>DARKGRAY</TT> adds
 * 8 to the its value making dark colors light.
 * @see COLORS
 * @see lowvideo
 */
void highvideo (void);

/**
 * Makes foreground colors dark.
 * If the current foreground color is higher than <TT>LIGHTGRAY</TT> substracts
 * 8 from its value making light colors dark.
 * @see COLORS
 * @see highvideo
 */
void lowvideo (void);

/*@{*/
/*
 * You may need to link with libmsvcr70.a or libmsvcr70d.a or libmsvcr71.a
 *  or libmsvcr71d.a if you want any of these functions.
 */
#ifdef UNICODE
_CRTIMP wchar_t * __cdecl         _cgetws(wchar_t *);
_CRTIMP unsigned short __cdecl    _getwch(void);
_CRTIMP unsigned short __cdecl    _getwche(void);
_CRTIMP unsigned short __cdecl    _putwch(wchar_t);
_CRTIMP unsigned short __cdecl    _ungetwch(unsigned short);
_CRTIMP int __cdecl               _cputws(const wchar_t *);
_CRTIMP int __cdecl               _cwprintf(const wchar_t *, ...);
_CRTIMP int __cdecl               _cwscanf(const wchar_t *, ...);
#endif
/*@}*/

/**
 * Pauses program execution for a given time.
 * @see switchbackground
 * @param ms miliseconds
 */
void delay (int ms);

/**
 * Replaces background color in the whole window. The text however
 * is left intact. Does not modify textbackground().
 * @see flashbackground
 * @param color background color
 */
void switchbackground (int color);

/**
 * Changes background color for a given time and then it restores it back.
 * You can use it for visual bell. Does not modify textbackground().
 * @see switchbackground
 * @see delay
 * @param color background color
 * @param ms miliseconds
 */
void flashbackground (int color, int ms);

/**
 * Clears the keyboard buffer.
 * To see it in effect run <TT>conio_test</TT> and try to press a key during
 * the 'Flashing...' phase.
 */
void clearkeybuf (void);

#ifdef __cplusplus
}
#endif

#endif /* _CONIO2_H_ */
 143  
Railway reservation system/main.c
@@ -0,0 +1,143 @@
#include <stdio.h>
#include <stdlib.h>
#include"rlyres.h"
#include"conio2.h"

int main()
{
    int choice;
    int ti;


    passenger* ptr;


add_trains();
    while(1)
    {
        choice=enterchoice();
        if(choice==9)
            exit(0);
        switch(choice)
        {

        case 1:
            {
clrscr();
             view_train();
             break;
             }

        case 2:
             {
                clrscr();
                 ptr=get_passenger_details();
                if(ptr!=NULL)
                {
                     ti=book_ticket(*ptr);
                 if(ti==-1)
                    printf("Booking Failed");
                    break;
                }

break;
}

        case 3:
            {
                clrscr();

                 ti=accept_ticket_no();
                  if(ti!=0)
                  {
                      view_ticket(ti);

                  }

break;

            }

        case 4:
            {

clrscr();
                 char* mob_no=accept_mobile_no();
                 if(mob_no==NULL)
                    break;

              int *ti_no=get_ticket_no(mob_no);
              if(ti_no==NULL)
                break;
              printf("\nYOUR TICKET NO IS:%d",*ti_no);
              getch();
              break;


            }



        case 5:
            {


            clrscr();
            view_all_booking();
            break;
            }
        case 6:
            {  clrscr();
             char* train_no=accept_train_no();
             view_train_bookings(train_no);

            break;
            }
        case 7:
            {  clrscr();

               ti=accept_ticket_no();
               int temp=cancel_ticket(ti);
               if(temp==1)
               {
                   printf("NO BOOKING HAS BEEN FOUND TO TICKET NO: %d",ti);
                   getch();
                   break;
               }
               else
                printf("\nTICKET HAS BEEN CANCELED SUCCESSFULLY");
                getch();
                break;



            }



        case 8:
            {
                clrscr();
              char *tr_no=accept_train_no();
           int check=cancel_train(tr_no);
           if(check==0)
            printf("\nNo train is found with this no %s",tr_no);
           else
            printf("\nTRAIN %s HAS BEEN CANCELED SUCCESSFULY",tr_no);
           getch();

            break;
            }

        default:
            textcolor(LIGHTRED);
            printf("wrong choice! please try again\n");
            getch();
            clrscr();
        }

    }


    return 0;
}
 BIN +14.4 KB 
Railway reservation system/obj/Debug/conio.o
Binary file not shown.
 BIN +4.89 KB 
Railway reservation system/obj/Debug/main.o
Binary file not shown.
 BIN +21.8 KB 
Railway reservation system/obj/Debug/rlyres.o
Binary file not shown.
 871  
Railway reservation system/rlyres.c
Large diffs are not rendered by default.

 46  
Railway reservation system/rlyres.h
@@ -0,0 +1,46 @@
#ifndef RLYRES_H_INCLUDED
#define RLYRES_H_INCLUDED
struct train
{
    char train_no[10];
    char from[10];
    char to[10];
    int fac_fare;
    int sac_fare;
}; typedef struct train train;
struct passenger
{
    char p_name[20];
    char gender;
    char train_no[10];
    int age;
    char mob_no[12];
    char p_class;
    int ticketno;
    char address[20];

};
typedef struct passenger passenger;
int enterchoice();
void add_trains();
void view_train();
int book_ticket(struct passenger);
int* get_ticket_no(char*);
void view_ticket(int);
void view_all_booking();
void view_booking(char*);
int canel_ticket(int);
int cancel_train(char*);
int check_train_no(char*);
passenger* get_passenger_details();
int get_booked_ticket_count(char*,char);
int last_ticket_no();
int check_mob_no(char*);
char* accept_train_no();
int accept_ticket_no();
int search_ticket_no(char*);
char* accept_mobile_no();
void view_train_bookings(char*);


#endif // RLYRES_H_INCLUDED
