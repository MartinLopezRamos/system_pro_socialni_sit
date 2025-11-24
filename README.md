# Informační systém pro sociální síť **SafeConnect**

## Krátký popis
SafeConnect je jednoduchý informační systém navržený pro bezpečnou registraci uživatelů na sociální síti, s důrazem na ochranu osobních údajů, silné zabezpečení účtů a správu uživatelských profilů.

---

## Cíl systému a cílová skupina
**Cílová skupina:**  
- Uživatelé sociální sítě (běžní uživatelé)  
- Administrátoři platformy  

**Cíl systému:**  
- Poskytovat bezpečný proces registrace a přihlášení uživatelů.  
- Zajistit správu účtů a ochranu dat prostřednictvím moderních bezpečnostních mechanismů.  
- Uchovávat uživatelské informace v bezpečné databázi, která zabraňuje neoprávněnému přístupu.  
- Umožnit administrátorům kontrolu uživatelských účtů, ověřování a řešení bezpečnostních incidentů.

---

## Základní funkce (Role a oprávnění)

### **Běžný uživatel**
- Registrace nového účtu (email, heslo, přezdívka).  
- Přihlášení pomocí emailu a hesla.  
- Ověření emailové adresy prostřednictvím ověřovacího odkazu.  
- Obnovení hesla pomocí zabezpečeného resetovacího tokenu.  
- Upravení vlastního profilu (avatar, bio, přezdívka).  
- Zobrazení základních bezpečnostních informací (poslední přihlášení, aktivní zařízení).

### **Administrátor**
- Správa uživatelů (zobrazení, deaktivace, blokace účtů).  
- Kontrola stavu ověření emailů.  
- Resetování zabezpečení účtu nebo vynucení změny hesla.  
- Přehled bezpečnostních alertů (podezřelé přihlášení, více pokusů o heslo).  
- Monitoring základních logů (registrace, přihlášení, obnovení hesla).

---

## Spravovaná data (Příklady)
- **Uživatelé:**  
  - email  
  - hash hesla  
  - stav ověření emailu  
  - datum registrace  
  - profilové informace (přezdívka, avatar, bio)  
  - bezpečnostní logy (poslední přihlášení, IP, zařízení)

- **Bezpečnostní tokeny:**  
  - resetovací tokeny pro obnovu hesla  
  - ověřovací tokeny pro aktivaci účtu  
  - doby platnosti tokenů

- **Logy přístupů a událostí:**  
  - neúspěšné pokusy o přihlášení  
  - změny hesla  
  - úpravy profilu  
  - administrátorské zásahy

- **Odkaz ná návrh ve figmě:**  
  https://www.figma.com/design/PPfZNge6vPPvYtt8hb9V5j/Untitled?node-id=0-1&p=f
