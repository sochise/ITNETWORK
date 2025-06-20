Tady máš tvůj návod přehledně zapsaný v Markdownu – můžeš ho rovnou vložit do README.md nebo jiné dokumentace:

# 🛠️ Návod: Jak propojit existující složku se soubory s GitHubem

Tento návod popisuje, jak verzovat projekt pomocí Gitu a propojit ho s GitHubem, pokud už máš ve složce existující soubory a provedl jsi `git init`.

---

## 1. Přidej všechny soubory do Git

```bash
git add .
```

⸻

2. Proveď první commit
```bash
git commit -m "První commit – přidání existujících souborů"
```

⸻

3. Vytvoř nový repozitář na GitHubu
	1.	Přejdi na: https://github.com/new
	2.	Zadej název repozitáře (např. prvni_web)
	3.	Nezaškrtávej volbu Initialize with a README (protože soubory už máš u sebe)

⸻

4. Propoj lokální složku s GitHubem

Zkopíruj URL repozitáře (např. https://github.com/blahoslavsocha/prvni_web.git) a zadej:

git remote add origin https://github.com/blahoslavsocha/prvni_web.git


⸻

5. Nahraj (pushni) projekt na GitHub

Pokud používáš větev master:
```bash
git push -u origin master
```
Pokud máš větev main:
```bash
git push -u origin main
```

⸻

6. Ověř propojení (volitelný krok)
```bash
git remote -v
```

⸻

✅ Hotovo! Projekt je nyní verzovaný a napojený na GitHub.

Chceš k tomu přidat i `.gitignore`, nebo to rovnou spojit s GitHub Actions?