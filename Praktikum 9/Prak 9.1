#include <ncurses\curses.h>	
#include <string>	
using namespace std;

int main() {
	int x = 10, y = 10; 	// posisi awal teks
	int ch;
	// inisisalisasi ncurses
	initscr();				// memulai mode ncurses
	
	// mengaktifkan mode input mentah (menerima input apa adanya)
	raw();
	
	// mengaktifkan penangkapan tombol khusus seperti panah
	keypad(stdscr, TRUE);
	
	// mencegah karakter yang ditekan muncul di layar
	noecho();
	
	// instruksi awal
	mvprintw(0, 0, "Gunakan tombol panah untuk menggerakkan teks. Tekan 'q' untuk keluar.");
	
	// loop untuk menangani input dan pergerakan
	while((ch= getch()) != 'q') {
		// membersihkan layar setiap kali pergerakan terjadi
		clear();
		
		refresh();
		
		mvprintw(0, 0, "Gunakan tombol panah untuk menggerakkan teks. Tekan 'q' untuk keluar");
		
		// memeriksa tombol yang ditekan dan memperbarui posisi
		switch(ch) {
			case KEY_UP:
				y = (y > 0) ? y - 1 : y;	// mencegah keluar dari batas atas
				break;	// bergerak ke atas
			case KEY_DOWN:
				y = (y < LINES - 1) ? y + 1 : y;	// mencegah keluar dari batas bawah
				break;	// bergerak ke bawah
			case KEY_LEFT:
				x = (y > 0) ? x - 1 : x;	// mencegah keluar dari batas kiri
				break;	// bergerak ke kiri
			case KEY_RIGHT:
				x = (y < COLS - 1) ? x + 1 : y;		// mencegah keluar dari batas kanan
				break;	// bergerak ke kanan
		}
		
		// debugging
		string xTemp = to_string(x);
		string yTemp = to_string(y);
		string chTemp = to_string(ch);
		
		mvprintw(1, 0, "x : ");
		mvprintw(1, 4, xTemp.c_str());
		
		mvprintw(2, 0, "y : ");
		mvprintw(2, 4, yTemp.c_str());
		
		mvprintw(3, 0, "in : ");
		mvprintw(3, 4, chTemp.c_str());
		
		//menampilkan 'x' pada posisi (y,x)
		mvprintw(y, x, "x");
		
		//meng-update tampilan
		refresh();
		
	}	
	
	// mengakhiri mode ncurses
	endwin();
	
	return 0;
}

