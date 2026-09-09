# 📊 Równanie na zamówieniach

Makro Rownanie_na_zamowieniach() automatyzuje kolejne etapy procesu równania zamówień w pliku Excel.

Dzięki automatyzacji proces obejmujący przygotowanie danych, ich przetworzenie oraz wykonanie kolejnych kroków równania zamówień może zostać wykonany za pomocą jednego przycisku. Po zakończeniu działania zostanie wyświetlony komunikat potwierdzający wykonanie wszystkich kroków.

## 🚀 Kolejne kroki makra do równania na zamówieniach:

1️⃣	Z pliku z zamówieniami „daty zamówień”, wykorzystywanego podczas równania zamówień, skopiuj wartości z zakładek i wklej jako wartości do odpowiednich zakładek:
  * Fin Rcpt do wklejenia 26P2	Dane dotyczące odpowiedniego okresu
  * Fin Rcpt do wklejenia 27P1	Dane dotyczące odpowiedniego okresu

⚠️ WAŻNE: Po zakończeniu każdego półrocza należy zaktualizować w kodzie makra numery tygodni, tak aby odpowiadały aktualnie analizowanemu okresowi.

2️⃣	Pobierz aktualny zrzut z MFP, a następnie wklej go do odpowiedniej zakładki w pliku Excel.

3️⃣	Po wykonaniu powyższych czynności przejdź do zakładki „Button” i uruchom przyciskiem makro „Rownanie_na_zamowieniach()”.
Makro automatycznie utworzy nową zakładkę, przetworzy wprowadzone dane, wykona kolejne etapy procesu równania zamówień i zwróci komunikat, że wszystkie kroki zostały wykonane.

