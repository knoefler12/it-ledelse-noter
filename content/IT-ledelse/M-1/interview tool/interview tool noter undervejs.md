implement mps

Vi satte flere transskriptionsmodeller op i appen, så vi kunne køre dem på samme lydfil, gemme resultaterne hver for sig og sammenligne dem. Det gav os mulighed for at afprøve Whisper small, Edda, Hviske og en dansk finjusteret Whisper-model uden at overskrive tidligere transskriptioner.

Den danske Whisper-model har indtil nu givet de bedste resultater i vores brug. Med M2 Max-acceleration transskriberede den en lydfil på 2 minutter og 45 sekunder på cirka 36 sekunder, mod cirka 4 minutter og 40 sekunder på CPU. Derfor har vi besluttet at forenkle programmet omkring den model

