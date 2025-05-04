
---

# Keisa Syntax Documentation  
*A lightweight documentation format with clean syntax highlighting.*

---

## **Syntax Elements**  

### 1. Headings  
```keisa
# Heading 1  
## Heading 2  
### Heading 3  
```
- Start with `#`
- Allowed any length!

### 2. Lists / Parameters  
```keisa
- List item  
- Another item  
```
- Start with `-`  

### 3. Comments / Quotes  
```keisa
> This is a comment  
> Can span multiple lines  
```
- Start with `>`  

### 4. Text Formatting  
```keisa
*bold text*  
`italic text`  
```
- `*text*` → Bold
- `` `text` `` → Italic

### 5. Variable Declarations  
```keisa
$ type name  
$ int counter  
$ string username  
```
- Structure: `$ type name`  
- Used to document data structures

### 6. Labels  
```keisa
main:  
config:  
```
- Format: `label:`  
- Used to group related content

### 7. Numeric Literals  
```keisa
42          (decimal)  
0b1010      (binary)  
0o755       (octal)  
0xFF        (hex)  
3.14        (float)  
```

### 8. Plain Text  
Any text not matching other rules.  

---

## **Why "Keisa"?**  
The name comes from Japanese **「軽さ」** (lightness), reflecting:  
- Minimalist syntax  
- Easy-to-read formatting  
- Lightweight parsing  

---