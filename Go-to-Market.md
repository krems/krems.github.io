1. Сохранённые карты наших клиентов, какая никакая база
2. У нас уже есть написанный движок и куча интеграций по всему миру
3. У нас есть хороший API на уровне провайдеров, типа stripe и checkout. При том, что мы находимся в регионах, где тот же страйп не оперирует
4. Регуляторные риски, у нас ниже, мы в целом, наверное, можем работать с теми, с кем тот же страйп/чекаут, работать не хочет
5. Какой-никакой эффект масштаба. У нас система уже построена. Обслуживание, судя по всему, не очень дорогое, потому что мы всё равно обслуживаем такую же штуку для себя
6. Надежность в смысле аптайма, зависающих платежей и реестров для реконсиляции
Конкретно для Колумбии:
7. Доступ к международным и мультивалютным платежам
8. Нанимаем локальный саппорт
9. Интегрируем QR и  DaviPlata
10. У нас есть мобильные (Android/iOS) и Web SDK с адаптивным чекаутом
11. У нас есть Apple Pay и Google Pay
12. Будем интегрировать PSE и, возможно, Baloto
13. Фокусируемся на быстром онбординге
14. Можем вести средне-агрессивную ценовую политику (нижний диапазон 3-3.5% комиссии и дешевые фиксы)


**Рекомендуемая go-to-market стратегия:**
1. **Partnership approach**: используем регуляторную песочницу и партнерство с местными игроками для быстрого старта
2. **Geographic focus**: начинаем с Bogotá и Medellín, где больше всего SME
3. **Vertical penetration**: ищем клиентов с высоким оборотом транзакций (delivery, retail)
4. **Freemium model**: No monthly fees, competitive per-transaction pricing
5. **Digital-first customer acquisition**: Online marketing, referral programs, social media presence

**Key differentiators для успеха**: Superior customer experience, transparent pricing, fast onboarding, reliable technology, и deep understanding SME pain points в Colombia market.




# Анализ пяти сил Портера для PSP в сегменте SME C2B платежей Колумбии

SME сегмент в Колумбии характеризуется высокой фрагментацией, ограниченными техническими ресурсами и острой чувствительностью к стоимости, что создает уникальные возможности для специализированных PSP решений.

## Угроза новых участников

### **Оценка: НИЗКАЯ (2/5)**

SME-фокусированный подход для C2B платежей значительно снижает барьеры входа по сравнению с корпоративным сегментом. Технологические требования менее сложные - SME бизнесы обычно довольствуются стандартными API интеграциями и не требуют кастомизированных решений корпоративного уровня. Это позволяет новым участникам создавать MVP решения с бюджетом $50,000-200,000 вместо $500,000+ для корпоративных PSP.

Регулятивные требования для SME сегмента менее строгие. Большинство SME обрабатывают объемы ниже пороговых значений для enhanced due diligence, что упрощает onboarding и снижает compliance расходы. Участие в regulatory sandbox SFC особенно выгодно для SME-ориентированных решений, поскольку позволяет тестировать упрощенные процедуры KYC.

Однако доступ к банковскому спонсорству остается барьером. Банки предпочитают работать с PSP, имеющими track record и гарантированные объемы. Для SME-фокусированного PSP необходимо продемонстрировать четкую стратегию масштабирования и прогнозируемые объемы минимум $10-20 млн в год.

Конкурентное преимущество новых участников может заключаться в лучшем понимании специфических потребностей SME: простота интеграции, понятный pricing, быстрый onboarding и персонализированная поддержка на испанском языке.

## Рыночная власть поставщиков

### **Оценка: СРЕДНЕ-ВЫСОКАЯ (3.5/5)**

Для SME-ориентированного PSP зависимость от банковских партнеров остается высокой, но появляются альтернативные стратегии снижения этой зависимости. SME бизнесы менее требовательны к банковскому разнообразию - достаточно партнерств с 2-3 основными банками (Bancolombia, Banco de Bogotá, Davivienda) для покрытия 70%+ потребностей рынка.

Переговорная позиция с банками слабее чем у корпоративных PSP из-за меньших гарантированных объемов. Однако SME сегмент привлекателен для банков своим ростом - количество SME в Колумбии превышает 2.5 млн компаний, и многие еще не цифровизированы. Это создает возможности для получения льготных условий в обмен на help with SME acquisition.

Альтернативные поставщики инфраструктуры (fintech-as-a-service провайдеры) становятся viable option. Stripe Connect, Adyen MarketPay или локальные solutions как PlacetoPay White Label могут обеспечить faster time-to-market с меньшими прямыми банковскими интеграциями.

Стоимость эквайринга для SME обычно выше корпоративных тарифов на 0.2-0.5% из-за меньших объемов и higher perceived risk. Типичные банковские тарифы для SME: 2.2-2.8% для кредитных карт и 1.0-1.5% для дебетовых карт.

## Рыночная власть покупателей

### **Оценка: СРЕДНЯЯ (3/5)**

SME демонстрируют парадоксальную переговорную силу - индивидуально они слабы, но как сегмент представляют attractive market opportunity. Типичный SME (оборот $50,000-500,000 в год) не имеет leverage для индивидуальных тарифов, но высокая конкуренция среди PSP создает стандартизированные конкурентные предложения.

Стоимость переключения для SME относительно низкая благодаря стандартизации e-commerce платформ (WooCommerce, Shopify, PrestaShop). Большинство SME используют готовые solutions с plug-and-play PSP интеграциями, что делает смену провайдера вопросом нескольких дней или недель.

Ценовая чувствительность в SME сегменте extremely high. Разница в 0.2-0.3% комиссии может быть решающим фактором выбора PSP. SME часто sacrifice advanced features ради lower pricing, что создает opportunity for value-based positioning.

Decision-making процесс в SME более простой и быстрый - обычно решение принимает владелец или top manager без lengthy procurement процедур. Это создает возможности для агрессивного direct sales подхода и quick wins.

Требования к функциональности ограничены базовыми потребностями: прием основных payment methods (карты, PSE, цифровые кошельки), basic fraud protection, простая отчетность и fast settlement. Advanced features как machine learning fraud detection или sophisticated analytics are nice-to-have, не must-have.

## Угроза товаров-заменителей

### **Оценка: ОЧЕНЬ ВЫСОКАЯ (5/5)**

SME сегмент особенно уязвим к товарам-заменителям из-за lower switching costs и limited technical expertise для evaluation of complex solutions. Cash-on-delivery остается доминирующим методом для многих SME, особенно в регионах и для businesses с низкой digital maturity. Доля COD в некоторых категориях превышает 60%.

Прямые банковские решения представляют серьезную угрозу. Bancolombia's Wompi специально designed for SME с simplified onboarding и competitive pricing. Banco de Bogotá и Davivienda also developing SME-focused payment solutions, leveraging their existing customer relationships.

Цифровые кошельки (Nequi, DaviPlata) агрессивно продвигают merchant solutions для SME. Nequi Cobros позволяет accept payments через QR codes с minimal setup и commission от 1.5%, что существенно ниже traditional PSP rates. DaviPlata предлагает similar functionality с integration в существующую Davivienda ecosystem.

Social commerce и messaging platforms создают alternative payment flows. WhatsApp Business позволяет SME accept payments через direct bank transfers или digital wallets, bypassing traditional PSP infrastructure. Instagram Shopping и Facebook Marketplace также integrate payment functionality.

Peer-to-peer платежные системы становятся attractive для service-based SME. Транспортные услуги, рестораны и retail могут использовать QR-based solutions от финтехов или даже crypto payments для избежания traditional payment processing fees.

## Конкурентное соперничество

### **Оценка: ОЧЕНЬ ВЫСОКАЯ (5/5)**

SME сегмент характеризуется intense competition с multiple layers конкурентов. Traditional PSP players (PayU, PlacetoPay, ePayco) активно compete за SME market share через агрессивные pricing strategies и simplified onboarding processes. PayU Latam's "Pago Fácil" specifically targets micro and small businesses с комиссиями от 2.4%.

Banking incumbents наступают с dedicated SME solutions. Bancolombia's ecosystem включает Wompi для payments, Nequi для digital wallet functionality, и traditional banking services, создавая comprehensive offering трудно compete против. Davivienda's partnership с ePayco provides similar integrated approach.

Финтех стартапы агрессивно target SME segment с disruptive pricing models. Некоторые предлагают freemium models или transaction-based pricing без monthly fees, что attractive для small volume merchants. Others focus на specific verticals (restaurants, retail, services) с tailored solutions.

International players входят в рынок через partnerships или direct expansion. Stripe, Square, и другие global PSP рассматривают Latin America как growth market и may target SME segment для quick market penetration.

Price competition особенно intense - некоторые players готовы work с minimal margins для market share acquisition. Commission rates для SME снизились с 3.5-4% до 2.5-3% за последние два года, что pressure profitability across the sector.

Product differentiation challenging в SME сегменте из-за standardized needs. Competition increasingly focus на service quality, onboarding speed, customer support quality, и additional value-added services (invoicing, inventory management, basic CRM).

## Заключение и стратегические выводы

**Общая привлекательность рынка: СРЕДНЯЯ (3.2/5)**

Фокус на SME C2B платежи создает mixed picture - lower barriers to entry и large addressable market, но intense competition и high threat of substitutes. Ключевые стратегические insights:

**Уникальные возможности SME сегмента:**
- 2.5+ млн SME в Колумбии с low digital payment penetration
- Regulatory sandbox особенно beneficial для SME-focused innovations
- Faster decision-making cycles и direct access к decision makers
- High growth potential - SME digital payments растут на 25%+ annually

**Критические success factors:**
- **Ultra-competitive pricing**: Target commission rates 2.0-2.3% для market penetration
- **Plug-and-play integration**: Maximum 48-hour onboarding process
- **Local support**: Spanish-speaking customer service и local market understanding
- **Vertical specialization**: Focus на specific SME categories (restaurants, retail, services)
- **Value-added services**: Beyond payments - invoicing, inventory, basic analytics

**Рекомендуемая go-to-market стратегия:**
1. **Partnership approach**: используем
2. **Geographic focus**: Start с Bogotá и Medellín где highest SME density
3. **Vertical penetration**: Target high-transaction frequency businesses (delivery, retail)
4. **Freemium model**: No monthly fees, competitive per-transaction pricing
5. **Digital-first customer acquisition**: Online marketing, referral programs, social media presence

**Key differentiators для успеха**: Superior customer experience, transparent pricing, fast onboarding, reliable technology, и deep understanding SME pain points в Colombia market.

