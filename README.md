#include <stdio.h>

// 1. Deklarasi Enum untuk Tingkat Prioritas Tugas
typedef enum {
    RENDAH,
    SEDANG,
    TINGGI,
    URGENT
} PrioritasTugas;

int main() {
	 PrioritasTugas prioritas = RENDAH;
	switch(prioritas) {
		case RENDAH: printf("DIKUMPULKAN SATU MINGGU KEMUDIAN\n"); break;
		case SEDANG: printf("DIKUMPULKAN EMPAT-TIGA HARI KEMUDIAN\n"); break;
		case TINGGI: printf("DIKUMPULKAN HARI INI\n"); break;
		case URGENT: printf("DIKUMPULKAN 30 MENIT LAGI"); break;
		
	}
    return 0;
}
