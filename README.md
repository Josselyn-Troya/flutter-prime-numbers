# Números Primos

### Función principal
```
 void _incrementCounter() {
    int _count = 0;
    int _n = new Random().nextInt(100);
    for (var i = 1; i <= _n; i++) {
      if (_n % i == 0) {
        _count++;
      }
    }
    if (_count == 2) {
      setState(() {
        _prime = _n;
      });
    } else {
      _incrementCounter();
    }
  }
```
### Genera números primos al azar al hacer clic en el tap

### ![](https://github.com/Josselyn-Troya/flutter-prime-numbers/blob/main/images/primos1.png)
### ![](https://github.com/Josselyn-Troya/flutter-prime-numbers/blob/main/images/primos2.png)
### ![](https://github.com/Josselyn-Troya/flutter-prime-numbers/blob/main/images/primos3.png)



