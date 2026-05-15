# GitHub Copilot Ücretlendirme Seçenekleri: Kapsamlı Rehber Mayıs-2026

---

## **🚀 Önemli Bir Not: Hap Bilgi Paylaşımı**

Genelde yazılar böyle başlar: "Detaylar için aşağıdaki linklere bakın!" ve ben de size ansiklopedinin kütüphanedeki raf numarasını göstermiş olurum. Ancak burada asıl amacım **sizlere ansiklopedinin raf numarasını vermek değil, içindeki hap bilgiyi paylaşmak** 💊

---

### **GitHub Copilot'ın Yeni Ücretlendirme Modeli**

Haziran 2026'dan itibaren, Copilot'ın ücretlendirme sistemi tamamen yeniden düzenleniyor. Eğer Copilot kullanan bir organizasyon veya bireysel geliştirici iseniz, bu değişiklikleri anlamak oldukça önemli hale geliyor.

---

## 🔄 **Değişim: İstek Bazlı modelden Kullanım Bazlı modele geçiş**

1 Haziran 2026'dan itibaren GitHub, Copilot'ın ücretlendirme modelini değiştiriyor. Eski sistem artık geride kalıyor; yeni dönemde **kullandığınız her token için ödeme yapacaksınız**. Bu model hem bireysel kullanıcılar hem de kurumlar için geçerli.

---

## 💳 **GitHub AI Credits: Yeni Faturalandırma Modeli**

### Temel Konsept

GitHub AI Credits, Copilot'ın yeni para birimi. İşin özü basitçe şöyle:

- **1 GitHub AI Credit = $0.01 USD**
- Her işlemin (input, output, cached) bir maliyeti vardır
- Model seçimi fiyatlandırmayı doğrudan etkiler

### Nasıl Çalışıyor?

Copilot ile her etkileşimde üç tür token tüketilir:

1. **Input Tokens**: Modele gönderdiğiniz metin
2. **Output Tokens**: Model tarafından üretilen yanıt
3. **Cached Tokens**: Model tarafından yeniden kullanılan veya depolanan içerik

Her token, kullanılan modele göre fiyatlandırılır ve toplam AI Credits'e dönüştürülür.

---

## 📊 **Plan Seçenekleri ve Dahil Edilen Krediler**

### Bireysel Planlar
- **Copilot Free**: Sınırlı kullanım
- **Copilot Pro**: $20/ay
- **Copilot Pro+**: Premium seçenek

### Kurumsal Planlar

| Plan | Aylık AI Credits/Kullanıcı | Promosyon (İlk 3 Ay) |
|------|---------------------------|----------------------|
| **Copilot Business** | 1,900 | 3,000 |
| **Copilot Enterprise** | 3,900 | 7,000 |

**Önemli Not:** Üyelik dahilindeki krediler, bireysel bütçe yerine **kurum düzeyinde birleştiriliyor**. Örneğin, 100 Copilot Business kullanıcısı = 190,000 credit paylaşımlı havuzdan harcayabilecek. Bu, kullanıcıların ihtiyaç duyduğu zaman daha fazla kredi tüketmesini, hafif kullanıcıların ise bunu dengelemesini sağlıyor.

---

## 🤖 **Model Seçenekleri ve Fiyatlandırma**

GitHub Copilot, farklı kurumlar tarafından sağlanan modeller sunuyor. Her modelin farklı maliyeti vardır:

### **OpenAI Modelleri**

| Model | Durum | Kategori | Input Token | Output Token | Cache Token |
|-------|-------|----------|-------------|--------------|-------------|
| **GPT-4.1** | GA | Çok yönlü | $2.00 | $0.50 | $8.00 |
| **GPT-5 mini** | GA | Hafif | $0.25 | $0.025 | $2.00 |
| **GPT-5.4** | GA | Çok yönlü | $2.50 | $0.25 | $15.00 |
| **GPT-5.5** | GA | Güçlü | $5.00 | $0.50 | $30.00 |

### **Anthropic Modelleri**

| Model | Durum | Kategori | Input Token | Output Token | Cache Token | Cache Write |
|-------|-------|----------|-------------|--------------|-------------|-------------|
| **Claude Haiku 4.5** | GA | Çok yönlü | $1.00 | $0.10 | $1.25 | $5.00 |
| **Claude Sonnet 4.6** | GA | Çok yönlü | $3.00 | $0.30 | $3.75 | $15.00 |
| **Claude Opus 4.7** | GA | Güçlü | $5.00 | $0.50 | $6.25 | $25.00 |

### **Google Modelleri**

| Model | Durum | Kategori | Input Token | Output Token | Cache Token |
|-------|-------|----------|-------------|--------------|-------------|
| **Gemini 2.5 Pro** | GA | Güçlü | $1.25 | $0.125 | $10.00 |
| **Gemini 3 Flash** | Ön İzleme | Hafif | $0.50 | $0.05 | $3.00 |

**💡 İpucu:** Tüm fiyatlar 1 milyon token başına verilmiştir. Hafif görevler için Gemini 3 Flash veya GPT-5 mini seçmek maliyetinizi önemli ölçüde düşürebilir.

---

## ✅ **Faturalandırılan Özellikler**

Aşağıdaki Copilot özellikleri AI Credits tüketir:

- 💬 **Copilot Chat**
- 🖥️ **Copilot CLI**
- ☁️ **Copilot Cloud Agent**
- 🏢 **Copilot Spaces**
- ⚡ **Spark**
- 🔧 **Üçüncü Taraf Coding Agents**
- 📝 **Copilot Code Review** (AI Credits + GitHub Actions dakikaları)

### 🆓 **Ücretsiz Olan Şeyler**

- **Code Completions**: Tüm ücretli planlar için **sınırsız**
- **Next Edit Suggestions**: Tüm ücretli planlar için **sınırsız**

---

Bütçe aşıldığında ne olur?

- **Ek Kullanıma İzin Veriliyorsa**: Kullanım devam eder, ek masraf faturalandırılır
- **Ek Kullanıma İzin Verilmiyorsa**: Erişim, sonraki faturalandırma dönemesine kadar bloke edilir

---

## 🎯 **Maliyet Tahmini Stratejileri**

### Senaryo 1: Basit Bir Soru
Bir hafif modelle (GPT-5 mini) çabuk bir soru sorarsanız:
- Inputlar: ~500 token
- Output: ~200 token
- **Toplam Maliyet**: ~0.15 AI Credit ($0.0015)

### Senaryo 2: Uzun Bir Coding Session
Claude Opus 4.7 ile çok dosyalı bir agentik session:
- Inputlar: ~50,000 token
- Output: ~10,000 token
- **Toplam Maliyet**: ~300 AI Credits ($3.00)

### Maliyeti Düşürmek İçin Öneriler
1. **Hafif modelleri seçin**: GPT-5 mini veya Gemini 3 Flash gibi
2. **Token caching'i kullanın**: Yeniden kullanılan içerik daha düşük maliyetle işlenir
3. **Bütçe limitleri ayarlayın**: Sürpriz masraflardan kaçının

---

## 🚀 **Mevcut Müşteriler İçin Tanımlanacak Promosyon**

Haziran 2026'da Copilot Business veya Enterprise kullanan mevcut müşteriler, ilk 3 ay (1 Haziran - 1 Eylül 2026) için **ekstra AI Credits alıyor**:

| Plan | İlk 3 Ay | Standart |
|------|----------|----------|
| Copilot Business | 3,000/kullanıcı | 1,900/kullanıcı |
| Copilot Enterprise | 7,000/kullanıcı | 3,900/kullanıcı |

---

## 🎓 **Ekip Yöneticileri İçin Aksiyonlar**

✅ **Haziran 2026'dan Önce Yapılması Gerekenler:**

1. **Bütçe stratejisini planlayın**: Ekibinizin ihtiyaçlarına göre bütçe limitlerini ayarlayın
2. **Model seçimini optimize edin**: Ekibiniz tarafından sık kullanılan görevler için en uygun modeli seçin
3. **Kullanıcı eğitimi**: Ekibinize token maliyetlerinin nasıl çalıştığını açıklayın
4. **İzlemeyi etkinleştirin**: GitHub Actions ve bilgi kullanım raporu aracılığıyla masrafları takip edin
5. **Promosyon döneminden yararlanın**: İlk 3 ayı deneme ve optimizasyon için kullanın

---

### 📚 **Kaynaklar**

- [GitHub Copilot Models and Pricing](https://docs.github.com/en/copilot/reference/copilot-billing/models-and-pricing)
- [Usage-Based Billing for Organizations and Enterprises](https://docs.github.com/en/copilot/concepts/billing/usage-based-billing-for-organizations-and-enterprises)

#GitHub #Microsoft #AI #ArtificialIntelligence #CopilotAI #TechBilling #SoftwareDevelopment #DevTools #CloudComputing #AIBilling #CodeGeneration #DeveloperTools #TechCommunity #Innovation #DigitalTransformation #Copilot

---
---

# GitHub Copilot Pricing Options: Comprehensive Guide May-2026

---

## **🚀 Important Note: Core Knowledge Sharing**

Usually, posts start like this: "Check the links below for details!" and I've shown you the shelf number in the encyclopedia. But here, my real goal is **not to give you the shelf number of the encyclopedia, but to share the core knowledge inside it** 💊

---

### **GitHub Copilot's New Pricing Model**

Starting June 2026, Copilot's pricing system is being completely redesigned. If you're an organization or individual developer using Copilot, understanding these changes becomes critically important.

---

## 🔄 **The Shift: From Request-Based to Usage-Based Billing**

Effective June 1, 2026, GitHub is changing Copilot's pricing model. The old system is now history; in the new era, **you'll pay for every token you consume**. This model applies to both individual users and enterprises.

---

## 💳 **GitHub AI Credits: The New Billing Unit**

### Core Concept

GitHub AI Credits are Copilot's new currency. Simply put:

- **1 GitHub AI Credit = $0.01 USD**
- Every interaction (input, output, cached) has a cost
- Model choice directly impacts pricing

### How It Works

With each Copilot interaction, three types of tokens are consumed:

1. **Input Tokens**: Text you send to the model
2. **Output Tokens**: Response generated by the model
3. **Cached Tokens**: Context the model reuses or stores

Each token is priced based on the model used and converted into AI Credits.

---

## 📊 **Plan Options and Included Credits**

### Individual Plans
- **Copilot Free**: Limited usage
- **Copilot Pro**: $20/month
- **Copilot Pro+**: Premium option

### Enterprise Plans

| Plan | Monthly AI Credits/User | Promotional (First 3 Months) |
|------|---------------------------|----------------------|
| **Copilot Business** | 1,900 | 3,000 |
| **Copilot Enterprise** | 3,900 | 7,000 |

**Important Note:** Included credits are pooled **at the organization level** rather than individual budgets. For example, 100 Copilot Business users = 190,000 shared credit pool. This allows power users to consume more when needed, while lighter users offset that consumption.

---

## 🤖 **Model Options and Pricing**

GitHub Copilot offers models from different providers. Each model has different costs:

### **OpenAI Models**

| Model | Status | Category | Input Token | Output Token | Cache Token |
|-------|--------|----------|-------------|--------------|-------------|
| **GPT-4.1** | GA | Versatile | $2.00 | $0.50 | $8.00 |
| **GPT-5 mini** | GA | Lightweight | $0.25 | $0.025 | $2.00 |
| **GPT-5.4** | GA | Versatile | $2.50 | $0.25 | $15.00 |
| **GPT-5.5** | GA | Powerful | $5.00 | $0.50 | $30.00 |

### **Anthropic Models**

| Model | Status | Category | Input Token | Output Token | Cache Token | Cache Write |
|-------|--------|----------|-------------|--------------|-------------|-------------|
| **Claude Haiku 4.5** | GA | Versatile | $1.00 | $0.10 | $1.25 | $5.00 |
| **Claude Sonnet 4.6** | GA | Versatile | $3.00 | $0.30 | $3.75 | $15.00 |
| **Claude Opus 4.7** | GA | Powerful | $5.00 | $0.50 | $6.25 | $25.00 |

### **Google Models**

| Model | Status | Category | Input Token | Output Token | Cache Token |
|-------|--------|----------|-------------|--------------|-------------|
| **Gemini 2.5 Pro** | GA | Powerful | $1.25 | $0.125 | $10.00 |
| **Gemini 3 Flash** | Preview | Lightweight | $0.50 | $0.05 | $3.00 |

**💡 Tip:** All prices are per 1 million tokens. Choosing Gemini 3 Flash or GPT-5 mini for lightweight tasks can significantly reduce your costs.

---

## ✅ **Billable Features**

The following Copilot features consume AI Credits:

- 💬 **Copilot Chat**
- 🖥️ **Copilot CLI**
- ☁️ **Copilot Cloud Agent**
- 🏢 **Copilot Spaces**
- ⚡ **Spark**
- 🔧 **Third-Party Coding Agents**
- 📝 **Copilot Code Review** (AI Credits + GitHub Actions minutes)

### 🆓 **What's Free**

- **Code Completions**: **Unlimited** for all paid plans
- **Next Edit Suggestions**: **Unlimited** for all paid plans

---

What happens when you exceed your budget?

- **Additional Usage Allowed**: Usage continues at published per-credit rates. Extra spending is charged to your organization
- **Additional Usage Not Allowed**: Access is blocked until the next billing cycle when monthly amounts refresh

---

## 🎯 **Cost Estimation Strategies**

### Scenario 1: Quick Question
Using a lightweight model (GPT-5 mini) for a quick query:
- Inputs: ~500 tokens
- Output: ~200 tokens
- **Total Cost**: ~0.15 AI Credit ($0.0015)

### Scenario 2: Long Coding Session
Extended agentic session with Claude Opus 4.7 across multiple files:
- Inputs: ~50,000 tokens
- Output: ~10,000 tokens
- **Total Cost**: ~300 AI Credits ($3.00)

### Tips to Reduce Costs
1. **Choose lightweight models**: GPT-5 mini or Gemini 3 Flash
2. **Use token caching**: Reused content is processed at lower rates
3. **Set budget limits**: Avoid surprise charges

---

## 🚀 **Promotional Offer for Existing Customers**

In June 2026, existing Copilot Business or Enterprise users will receive **extra AI Credits** for the first 3 months (June 1 - September 1, 2026):

| Plan | First 3 Months | Standard |
|------|----------|----------|
| Copilot Business | 3,000/user | 1,900/user |
| Copilot Enterprise | 7,000/user | 3,900/user |

---

## 🎯 **Budget Control: Stay Under Costs (Aikido Philosophy)**

When discussing AI topics at universities, I often reference Aikido philosophy: *"To overcome your opponent in Aikido, you must redirect their energy back to them."*

GitHub's new pricing policy embodies exactly this! GitHub redirects the energy of costs (your budget) back through a control system to your advantage. Your energy (budget) is transformed into your own advantage through proper limits and controls. The result? Control, power, and peace of mind—just like a well-executed Aikido move.

### **How Does It Work?**

GitHub offers budget controls at four levels:

1. **Enterprise-level**: Track spending for all organizations and cost centers
2. **Organization-level**: Track spending for all repositories in the organization
3. **Cost center-level**: Track spending for a single cost center
4. **User-level**: Track spending for individual users ($0 user budget = no access at all)

You can use budgets to get alerts as you approach limits and to enforce hard stops on usage. For example, if you want to allow some additional usage but keep it in check, you could set a user-level budget slightly above the included amount.

---

## 🤖 **What Does Copilot Itself Say?**

Let me have some fun. I asked GitHub Copilot how it views its new pricing system. Here's its "voice":

> *"Hey! Ready for me to explain my new billing model? Think of it this way: I'm a work of art. Human design (expensive), a simple question (cheap), or a long orchestration (really pricey). I'm not telling you the price—I'm telling you **the real cost**.*
>
> *In the old system, you'd ask "how many minutes?" Now you ask "how many tokens?" And you get all the details. You know the price, you can choose the model, you can control your budget.*
>
> *This is fair. This is transparent. And—in Aikido's language—this is understanding the source of energy."*

Pretty cool, right? 😎

---

## 💡 **Final Thoughts**

GitHub Copilot's new usage-based billing model is designed for organizations and developers who want to control costs while using resources efficiently. With transparent budget controls, a pooling system that optimizes flexibility, and diverse model options, Copilot offers a tailored solution for every size and needs profile.

**Key Message:** Make informed decisions. Understand your team's usage patterns, choose the right models, and set budget limits wisely. This way, you can harness the power of AI while keeping costs under control.

---

## 🎓 **Actions for Team Managers**

✅ **Before June 2026:**

1. **Plan your budget strategy**: Set budget limits based on your team's needs
2. **Optimize model selection**: Choose the best model for your team's frequent tasks
3. **User education**: Explain to your team how token costs work
4. **Enable monitoring**: Track spending through GitHub Actions and billing reports
5. **Leverage the promotional period**: Use the first 3 months to test and optimize

---

### 📚 **Resources**

- [GitHub Copilot Models and Pricing](https://docs.github.com/en/copilot/reference/copilot-billing/models-and-pricing)
- [Usage-Based Billing for Organizations and Enterprises](https://docs.github.com/en/copilot/concepts/billing/usage-based-billing-for-organizations-and-enterprises)

#GitHub #Microsoft #AI #ArtificialIntelligence #CopilotAI #TechBilling #SoftwareDevelopment #DevTools #CloudComputing #AIBilling #CodeGeneration #DeveloperTools #TechCommunity #Innovation #DigitalTransformation
