# PSEUDOCODE Javascript Game

```javascript
//pseudocode
CREATE FUNCTION 'perkenalan'
DECLARE name, age, capital THEN
DECLARE this.name AS name
DECLARE this.age AS age
DECLARE this,capital AS capital
  CREATE FUNCTION sayhello() THEN
  PRINT this.name
  END FUNCTION
  CREATE FUNCTION perkenalkan() THEN
  PRINT this.name
  END FUNCTION
  CREATE FUNCTION start THEN
    IF this.age <= 17 THEN
    PRINT 'Masih Muda'
    ELSE IF this.age >=17 AND this.age<=50 THEN
    PRINT this.capital
    ELSE
    PRINT 'terlalu tua'
    PRINT 'senang bertemu'
    END IF
  END FUNCTION
END FUNCTION

//JSON
DECLARE quiz1 AS JSON THEN
  CREATE pertanyaan AS ARRAY THEN
    DECLARE soal AS CHAR
    DECLARE jawaban AS CHAR
    DECLARE score AS INTEGER
  END
END

//JSON
DECLARE quiz2 AS JSON THEN
  CREATE pertanyaan AS ARRAY THEN
    DECLARE soal AS CHAR
    DECLARE jawaban AS CHAR
    DECLARE score AS INTEGER
  END
END
//main process
DECLARE pemain AS NEW FUNCTION OF perkenalan
DECLARE mcAcara AS NEW FUNCTION OF perkenalan
DECLARE jawaban1 AS ARRAY
DECLARE uang1 AS ARRAY
DECLARE hadiah VALUES 0
  FOR VARIABLE i VALEUS 0, i<4, i INCREMENT THEN
    PROMPT jawaban1 = quiz1.pertanyaan[i].soal
      IF jawaban[i] === quiz1.pertanyaan[i].jawaban THEN
        uang1[i]=quiz1.pertanyaan[i].scrore
      ELSE THEN
        uang1 VALUES 0
      END IF
      hadiah = hadiah + uang1[i]
  END FOR
  
DECLARE jawaban2 AS ARRAY
DECLARE uang2 AS ARRAY
DECLARE hadiah VALUES 0
  FOR VARIABLE j VALEUS 0, j<4, j INCREMENT THEN
    PROMPT jawaban2 = quiz2.pertanyaan[j].soal
      IF jawaban[j] === quiz2.pertanyaan[j].jawaban THEN
        uang2[j]=quiz2.pertanyaan[j].scrore
      ELSE THEN
        uang2 VALUES 0
      END IF
      hadiah = hadiah + uang2[j]
  END FOR
 
 DECLARE bonus AS INTEGER VALUES 5000000
 IF hadiah >=5000000 THEN
  hadiah = hadiah + bonus
 ELSE THEN
  hadiah
 END IF
 
 
```

**Berikut di atas adalah psudecode untuk quiz.js**
