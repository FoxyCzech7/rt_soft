**Systém pro rezervaci místností**

Tato aplikace umožňuje rezervování místností v budově. Uživatelé mohou přidávat nové rezervace, prohlížet existující rezervace a zrušit ty, které již nejsou potřeba.

**Funkce aplikace**

**Přidání nové rezervace:**
   - Vyplňte formulář se základními údaji:
     - **Název místnosti** (např. "Konferenční místnost 1")
     - **Datum rezervace** (ve formátu mm/dd/yyyy)
     - **Časový úsek** (např. 10:00:00 – 12:00:00, ve 24-hodinovém formátu)
     - **Vaše jméno**
   - Po odeslání formuláře bude rezervace přidána a zobrazená v seznamu v případě že nezdadáte špatné údaje (viz. validce a pravidla).

**Zobrazení všech rezervací:**
   - Všichni uživatelé mohou prohlížet seznam všech rezervací.
   - Rezervace jsou seřazeny podle data.
**Zrušení rezervace:**
   - Pokud chcete zrušit svou rezervaci, zadejte ID rezervace a klikněte na tlačítko "Zrušit rezervaci".

**Validace a pravidla**
- **Datum rezervace musí být v budoucnosti.**
- **Časový úsek musí být platný:** Čas začátku musí být před časem konce.
- **Žádné překrytí rezervací:** Ppokud je místnost již obsazena v daném čase, nebude možné provést rezervaci.
