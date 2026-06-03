# Calculadora CI

## Informe del Proyecto

Proyecto de calculadora con integración continua desarrollado con PHP, Composer, PHPUnit y GitHub Actions.

## Estructura del Proyecto

```
PARCIAL/
├── .github/workflows/
│   └── php-ci.yml        # Pipeline de Integración Continua
├── src/
│   └── Calculadora.php    # Clase Calculadora con 4 operaciones
├── tests/
│   └── CalculadoraTest.php # Pruebas unitarias (PHPUnit)
├── composer.json          # Dependencias del proyecto
└── README.md              # Documentación
```

## Funcionalidades Implementadas

- Sumar
- Restar
- Multiplicar
- Dividir (con validación de división por cero)

## Pruebas Unitarias

Se implementaron 5 pruebas unitarias con PHPUnit:

| Test | Descripción | Estado |
|------|-------------|--------|
| `testSuma` | Verifica que 2 + 3 = 5 | ✅ |
| `testResta` | Verifica que 4 - 3 = 1 | ✅ |
| `testMultiplicacion` | Verifica que 4 * 3 = 12 | ✅ |
| `testDivision` | Verifica que 6 / 3 = 2 | ✅ |
| `testDivisionPorCeroLanzaExcepcion` | Verifica que dividir por cero lanza `InvalidArgumentException` | ✅ |

## Badge

![CI Status](https://github.com/LUISVTP/MycalculatorParcial/actions/workflows/php-ci.yml/badge.svg)

## URL del Repositorio

https://github.com/LUISVTP/MycalculatorParcial

## Integrante

- Luis Felipe Bonilla Utria
