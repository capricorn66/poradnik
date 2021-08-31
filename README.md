# SK PORADNIK

### Jak uruchomić projekt?

1. zainstlować zależności z pliku package.json - uruchomić w konsoli: 'npm install'
2. uruchomienie projektu w wersji developmontu: 'npm start', w wersji produkcyjnej - 'npm run build'


### O projekcie

1. na sztywno są dodane style / skrypty z obecnej strony swisskrono.pl (style, BS 4.3.1, JQ 3.4.1)
2. zaktualizowany set ikon - icomoon (/app/icomoon) jest podłączony w pliku app.scss - należy go usunąć i zaktualizować ten pliku w głównym pliku scss w potoku scss w projekcie swisskrono
3. plugin swiper wymaga aktualizacji do wer. 3.4.2. Ta aktualizacja nie będzie miała wpływu na już istniejące konfiguracje i wywołania tego pluginu
4. plik swisskrono.scss - to jest baza styli, zaciągana z https://www.swisskrono.pl
5. bootstrap.scss, to BS w v4.3.1 - style zostały zmodyfikowane - dodany kolejny breakpoint - 'xxl'
