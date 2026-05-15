# Lumiola Forecast — Demo для Aquatonus

Standalone HTML-демо для Zoom-встречи с Еленой Анатольевной.

## Как запустить локально

Просто открыть `index.html` в браузере — всё работает офлайн (Tailwind через CDN, Inter через Google Fonts).

## Как поделиться публично

### Вариант 1 — Netlify (рекомендую)
1. Зайти на https://app.netlify.com/drop
2. Перетащить папку `aquatonus-demo` в окно
3. Получить публичный URL вида `random-name.netlify.app`
4. (опц.) В Settings → Site name переименовать в `lumiola-aquatonus`

Готово за 60 секунд. URL отправляешь Елене Анатольевне.

### Вариант 2 — Vercel
Аналогично: https://vercel.com/new → upload folder.

### Вариант 3 — GitHub Pages
1. Создать новый репо `lumiola-demo-aquatonus`
2. Закинуть index.html
3. Settings → Pages → Deploy from main
4. URL: `username.github.io/lumiola-demo-aquatonus`

## Содержимое демо (7 экранов — 3 фазы)

### Phase 1 — Pre-purchase (продажа курса)
1. **Welcome** — Aquatonus брендинг, объяснение что произойдёт за 5 минут
2. **InBody Result** — её цифры + cohort comparison «47 как ты»
3. **Face Analysis** — биологический возраст лица (38 при паспорте 32)
4. **Forecast Slider** — drag-slider «сегодня / через 8 недель»
5. **Personal Plan** — расписание курса + процедуры + цена 10К₽

### Phase 2 — During course (апселл)
6. **Week 3 Progress + LPG Upsell** — re-measure показывает прогресс, AI предлагает усилить курс +5 LPG за 7,400₽ (со скидкой −15% для курсовиков). Плюс secondary upsell к косметологу.

### Phase 3 — Post-course (retention + LTV)
7. **Course Complete** — финальный результат, топ-15% когорты, 3 опции:
   - Следующая «Перезагрузка» −20% (8К₽ вместо 10К₽)
   - Maintenance абонемент (2 LPG + 1 прессо/мес за 12.5К₽)
   - Премиум-апгрейд «Идеальный старт» −10% (36К вместо 40К)

Все цифры — мок-данные. В прод-версии тянутся из InBody + Face Analyzer + каталога Aquatonus.

## Цель демо

Показать **полную воронку LTV**: pre-purchase (×2 конверсия) → during course (upsells) → post-course (return + premium). Это и есть аргумент про прирост LTV с 16К до 32К на клиентку.

## Как использовать на Zoom (30 минут структура)

**0-10 мин:** Discovery вопросы (см. отдельный документ)

**10-25 мин:** Demo по экранам
- Phase 1 (3-4 мин): «вот что увидит клиентка в первые 5 минут после InBody»
  - На Forecast Slider — перетащить вручную (вау-момент)
- Phase 2 (2-3 мин): «вот что произойдёт на 3-й неделе»
  - Подчеркнуть: это не маркетинговая рассылка, это **рекомендация на основе её реальной реакции**
- Phase 3 (3-4 мин): «вот что произойдёт когда курс закончится»
  - Тут самая мощная часть — три параллельных upsell-канала
- Закрыть: «Phase 2 и 3 — это где приложение реально окупается. Phase 1 — это где оно продаёт идею»

**25-30 мин:** Условия пилота, следующий шаг
