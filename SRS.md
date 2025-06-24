# 📄 Software Requirements Specification (SRS)

## 1. Inngangur
### 1.1 Tilgangur
Lýsir tilgangi kerfisins og markmiðum þess.

### 1.2 Umfang
Stutt lýsing á því sem kerfið á að gera.

### 1.3 Skilgreiningar, skammstafanir og styttingar
| Hugtak | Skýring |
|--------|---------|
| SRS | Software Requirements Specification |

### 1.4 Tilvísanir
- IEEE 830 Standard

---

## 2. Almenn lýsing
### 2.1 Notendagerðir
- Notandi
- Kerfisstjóri

### 2.2 Rekstrarumhverfi
- Vefviðmót
- Geymsla í PostgreSQL

### 2.3 Hönnunarforsendur og takmarkanir
- Kerfið skal vera aðgengilegt í öllum helstu vöfrum.

---

## 3. Kröfur

### 3.1 Virkni (Functional Requirements)
| ID | Lýsing | Forgangur | Notandi |
|----|--------|-----------|---------|
| FR1 | Notandi skal geta skráð sig inn | MUST | Notandi |
| FR2 | Kerfið skal vista notendagögn | MUST | Kerfisstjóri |

### 3.2 Óvirkni (Non-Functional Requirements)
| ID | Lýsing | Mælikvarði |
|----|--------|------------|
| NFR1 | Kerfið skal vera tiltækt 99% tímans | Uptime > 99% |
| NFR2 | Viðbragðstími skal vera undir 1 sekúndu | Response < 1s |

### 3.3 Viðmót (User Interface Requirements)
- Notendaviðmót skal vera einfalt og aðgengilegt.

### 3.4 Öryggiskröfur
- Gagnaflutningur skal fara fram yfir HTTPS.

---

## 4. Viðaukar
### 4.1 Orðalisti
- "Notandi": Sá sem notar kerfið.

### 4.2 Samþykktir
- Kennari: ____________________
- Nemandi: ____________________
