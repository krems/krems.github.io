# Go-to-Market Strategy: PSP for SME C2B Payments in Colombia

*Date: September 21, 2025*  
*Folder: 1 - Projects/International PSP*

---

## Competitive Advantages

Based on our analysis, we have several key advantages for entering the Colombian market:

**General advantages:**
1. Saved cards of our clients, some kind of base
2. We already have a written engine and lots of integrations around the world
3. We have a good API at the provider level, like Stripe and Checkout. While we are in regions where Stripe doesn't operate
4. Regulatory risks are lower for us, we can generally probably work with those who Stripe/Checkout don't want to work with
5. Some scale effect. Our system is already built. Maintenance, apparently, is not very expensive because we service the same thing for ourselves anyway
6. Reliability in terms of uptime, hanging payments and registries for reconciliation

**Specifically for Colombia:**
7. Access to international and multi-currency payments
8. Hire local support
9. Integrate QR and DaviPlata
10. We have mobile (Android/iOS) and Web SDKs with adaptive checkout
11. We have Apple Pay and Google Pay
12. Will integrate PSE and possibly Baloto
13. Focus on fast onboarding
14. Can conduct moderately aggressive pricing policy (lower range 3-3.5% commission and cheap fixes)

**Recommended go-to-market strategy:**
1. **Partnership approach**: use regulatory sandbox and partnership with local players for quick start
2. **Geographic focus**: start with Bogotá and Medellín, where most SME are located
3. **Vertical penetration**: look for clients with high transaction turnover (delivery, retail)
4. **Freemium model**: No monthly fees, competitive per-transaction pricing
5. **Digital-first customer acquisition**: Online marketing, referral programs, social media presence

**Key differentiators for success**: Superior customer experience, transparent pricing, fast onboarding, reliable technology, and deep understanding of SME pain points in Colombia market.

# Porter's Five Forces Analysis for PSP in SME C2B Payments Segment in Colombia

The SME segment in Colombia is characterized by high fragmentation, limited technical resources and acute cost sensitivity, creating unique opportunities for specialized PSP solutions.

## Threat of New Entrants

### **Assessment: LOW (2/5)**

SME-focused approach for C2B payments significantly reduces entry barriers compared to the corporate segment. Technology requirements are less complex - SME businesses usually settle for standard API integrations and don't require customized enterprise-level solutions. This allows new entrants to create MVP solutions with a budget of $50,000-200,000 instead of $500,000+ for corporate PSPs.

Regulatory requirements for the SME segment are less stringent. Most SMEs process volumes below threshold values for enhanced due diligence, which simplifies onboarding and reduces compliance costs. Participation in SFC regulatory sandbox is particularly beneficial for SME-oriented solutions as it allows testing simplified KYC procedures.

However, access to banking sponsorship remains a barrier. Banks prefer to work with PSPs that have a track record and guaranteed volumes. For SME-focused PSPs, it's necessary to demonstrate a clear scaling strategy and predictable volumes of at least $10-20 million per year.

The competitive advantage of new entrants may lie in better understanding of specific SME needs: ease of integration, clear pricing, fast onboarding and personalized support in Spanish.

## Supplier Power

### **Assessment: MEDIUM-HIGH (3.5/5)**

For SME-oriented PSPs, dependence on banking partners remains high, but alternative strategies to reduce this dependence are emerging. SME businesses are less demanding in banking diversity - partnerships with 2-3 main banks (Bancolombia, Banco de Bogotá, Davivienda) are sufficient to cover 70%+ of market needs.

Negotiating position with banks is weaker than corporate PSPs due to smaller guaranteed volumes. However, the SME segment is attractive to banks due to its growth - the number of SMEs in Colombia exceeds 2.5 million companies, and many are not yet digitized. This creates opportunities to obtain preferential conditions in exchange for help with SME acquisition.

Alternative infrastructure suppliers (fintech-as-a-service providers) become a viable option. Stripe Connect, Adyen MarketPay or local solutions like PlacetoPay White Label can provide faster time-to-market with fewer direct banking integrations.

Acquiring costs for SMEs are usually 0.2-0.5% higher than corporate rates due to smaller volumes and higher perceived risk. Typical banking rates for SMEs: 2.2-2.8% for credit cards and 1.0-1.5% for debit cards.

## Buyer Power

### **Assessment: MEDIUM (3/5)**

SMEs demonstrate paradoxical bargaining power - individually they are weak, but as a segment they represent an attractive market opportunity. A typical SME (turnover $50,000-500,000 per year) has no leverage for individual rates, but high competition among PSPs creates standardized competitive offers.

Switching costs for SMEs are relatively low thanks to standardization of e-commerce platforms (WooCommerce, Shopify, PrestaShop). Most SMEs use ready-made solutions with plug-and-play PSP integrations, making provider switching a matter of days or weeks.

Price sensitivity in the SME segment is extremely high. A difference of 0.2-0.3% commission can be a decisive factor in PSP choice. SMEs often sacrifice advanced features for lower pricing, creating opportunities for value-based positioning.

Decision-making process in SMEs is simpler and faster - usually the owner or top manager makes the decision without lengthy procurement procedures. This creates opportunities for aggressive direct sales approach and quick wins.

Functionality requirements are limited to basic needs: acceptance of main payment methods (cards, PSE, digital wallets), basic fraud protection, simple reporting and fast settlement. Advanced features like machine learning fraud detection or sophisticated analytics are nice-to-have, not must-have.

## Threat of Substitutes

### **Assessment: VERY HIGH (5/5)**

The SME segment is particularly vulnerable to substitutes due to lower switching costs and limited technical expertise for evaluation of complex solutions. Cash-on-delivery remains the dominant method for many SMEs, especially in regions and for businesses with low digital maturity. COD share in some categories exceeds 60%.

Direct banking solutions present a serious threat. Bancolombia's Wompi is specifically designed for SMEs with simplified onboarding and competitive pricing. Banco de Bogotá and Davivienda are also developing SME-focused payment solutions, leveraging their existing customer relationships.

Digital wallets (Nequi, DaviPlata) aggressively promote merchant solutions for SMEs. Nequi Cobros allows accepting payments through QR codes with minimal setup and commission from 1.5%, which is significantly lower than traditional PSP rates. DaviPlata offers similar functionality with integration into the existing Davivienda ecosystem.

Social commerce and messaging platforms create alternative payment flows. WhatsApp Business allows SMEs to accept payments through direct bank transfers or digital wallets, bypassing traditional PSP infrastructure. Instagram Shopping and Facebook Marketplace also integrate payment functionality.

Peer-to-peer payment systems become attractive for service-based SMEs. Transportation services, restaurants and retail can use QR-based solutions from fintechs or even crypto payments to avoid traditional payment processing fees.

## Competitive Rivalry

### **Assessment: VERY HIGH (5/5)**

The SME segment is characterized by intense competition with multiple layers of competitors. Traditional PSP players (PayU, PlacetoPay, ePayco) actively compete for SME market share through aggressive pricing strategies and simplified onboarding processes. PayU Latam's "Pago Fácil" specifically targets micro and small businesses with commissions from 2.4%.

Banking incumbents advance with dedicated SME solutions. Bancolombia's ecosystem includes Wompi for payments, Nequi for digital wallet functionality, and traditional banking services, creating a comprehensive offering that's hard to compete against. Davivienda's partnership with ePayco provides a similar integrated approach.

Fintech startups aggressively target the SME segment with disruptive pricing models. Some offer freemium models or transaction-based pricing without monthly fees, which is attractive for small volume merchants. Others focus on specific verticals (restaurants, retail, services) with tailored solutions.

International players enter the market through partnerships or direct expansion. Stripe, Square, and other global PSPs consider Latin America as a growth market and may target the SME segment for quick market penetration.

Price competition is particularly intense - some players are ready to work with minimal margins for market share acquisition. Commission rates for SMEs have decreased from 3.5-4% to 2.5-3% over the last two years, pressuring profitability across the sector.

Product differentiation is challenging in the SME segment due to standardized needs. Competition increasingly focuses on service quality, onboarding speed, customer support quality, and additional value-added services (invoicing, inventory management, basic CRM).

## Conclusion and Strategic Insights

**Overall Market Attractiveness: MEDIUM (3.2/5)**

Focus on SME C2B payments creates a mixed picture - lower barriers to entry and large addressable market, but intense competition and high threat of substitutes. Key strategic insights:

**Unique SME Segment Opportunities:**
- 2.5+ million SMEs in Colombia with low digital payment penetration
- Regulatory sandbox particularly beneficial for SME-focused innovations
- Faster decision-making cycles and direct access to decision makers
- High growth potential - SME digital payments growing 25%+ annually

**Critical Success Factors:**
- **Ultra-competitive pricing**: Target commission rates 2.0-2.3% for market penetration
- **Plug-and-play integration**: Maximum 48-hour onboarding process
- **Local support**: Spanish-speaking customer service and local market understanding
- **Vertical specialization**: Focus on specific SME categories (restaurants, retail, services)
- **Value-added services**: Beyond payments - invoicing, inventory, basic analytics

**Recommended Go-to-Market Strategy:**
1. **Partnership approach**: Use regulatory sandbox and partnership with local players for quick start
2. **Geographic focus**: Start with Bogotá and Medellín where highest SME density
3. **Vertical penetration**: Target high-transaction frequency businesses (delivery, retail)
4. **Freemium model**: No monthly fees, competitive per-transaction pricing
5. **Digital-first customer acquisition**: Online marketing, referral programs, social media presence

**Key Differentiators for Success**: Superior customer experience, transparent pricing, fast onboarding, reliable technology, and deep understanding of SME pain points in Colombia market.