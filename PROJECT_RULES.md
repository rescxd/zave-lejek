# Project Design & Architecture System

## 1. Global Visual & Style Guidelines
- **Design Skill:** Podczas tworzenia każdego komponentu UI bezwzględnie stosuj zasady ze skilla `design-taste-frontend`.
- **Estetyka:** Minimalistyczna, profesjonalna, nowoczesna i przejrzysta (dużo whitespace / oddechu).
- **Kolorystyka:**
  - Background: Czysta biel (`#FFFFFF`) / bardzo delikatne szarości dla tła sekcji wtórnych.
  - Primary Accent: `#6F00FF` (używany precyzyjnie: CTA, akcenty, podświetlenia).
  - Text: Głęboka ciemna szarość / prawie czerń dla wysokiego kontrastu i czytelności.
- **Typografia:**
  - Main Font: Inter (odpowiednie grubości: 400 dla body, 500/600 dla UI, 700+ dla nagłówków).
  - Hierarchia: Wyraźny skok skali między H1, H2 i tekstem akapitowym.
- **Buttons Rule (Ograniczenie globalne):** Każdy przycisk na stronie MUSI posiadać pełne zaokrąglenie (`rounded-full` / `border-radius: 9999px`).
- **Animacje & Interakcje:**
  - Absolutny minimalizm w animacjach.
  - Brak agresywnych efektów wchodzenia.
  - Wyłącznie subtelne, płynne stany hover (np. `transition-colors duration-200`, delikatny micro-interaction na przyciskach/linkach).
- **Responsywność:** Mobile-first, pełna adaptacja do wszystkich rozdzielczości ekranu.

## 2. Page Structure & Sections

### Section 1: Hero Section
- **Wysokość:** Sekcja na pełną wysokość ekranu (`100vh` / `min-h-screen`), z kontrolowanym przelewaniem zawartości (overflow).
- **Układ (Pionowy, centrowany w poziomie):**
  1. **Logo:** Na samej górze, wyśrodkowane.
  2. **H2 Subtitle:** „Właścicielu studia detailingowego" (subtelniejszy nagłówek nad głównym).
  3. **H1 Headline (dwa wiersze):**
     - Wiersz 1: „Zarabiaj do 10 tysięcy więcej"
     - Wiersz 2: „bez marnowania czasu i pieniędzy"
  4. **Description:** „Lorem ipsum dolor sit amet, consectetur adipiscing elit. Proin eget gravida massa, a mollis"
  5. **Primary CTA Button:** „Zarezerwuj darmową rozmowę" (pełne zaokrąglenie `rounded-full`, kolor `#6F00FF`).
  6. **Social Proof (Pod przyciskiem):** 5 żółtych/złotych gwiazdek + tekst obok: „Trusted by 1,500 Happy Customers".
  7. **VSL Video Container:**
     - Placeholder ze zdjęciem tła oraz nakładką z ikoną PLAY na środku.
     - Zaokrąglone rogi kontenera video (`rounded-2xl` lub `rounded-xl`).
     - Cień / delikatne obramowanie podkreślające nowoczesność.
     - **Pozycjonowanie VSL:** Dół wideo ma wystawać w około 25% poniżej dolnej krawędzi sekcji Hero (efekt nachodzenia na kolejną sekcję).
