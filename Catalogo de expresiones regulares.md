# Expresiones regulares (regular expression)



## Eliminar espacios en blanco innecesarios

Elimina de un string los espacios en blanco innecesarios, dejando solo uno por palabra.

```
!'             a         '.replace(/\s+/g, '') // false
!'                   '.replace(/\s+/g, '') // true
!''.replace(/\s+/g, '') // true

'             a         '.replace(/\s+/g, '') // 'a'
'                   '.replace(/\s+/g, '') // ''
''.replace(/\s+/g, '') // ''

```
