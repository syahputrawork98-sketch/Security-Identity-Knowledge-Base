# 🛡️ Security & Identity: The Fortress of Application Integrity

> **"Security is not a feature; it is the foundation upon which all features are built."**

## 📖 Apa itu Security & Identity? (The What)
**Security & Identity** adalah disiplin pertahanan yang berfokus pada perlindungan integritas data, validasi identitas pengguna (Authentication), dan pengelolaan hak akses (Authorization). Ini mencakup penerapan kriptografi murni, mitigasi celah keamanan (AppSec), dan postur nirpercaya (*Zero Trust*) untuk memastikan sistem tetap kokoh di hadapan serangan siber.

Dalam ekosistem *The Learning Matrix*, Security-Identity-Knowledge-Base mewakili paradigma **Defense in Depth & Identity Sovereignty**: tentang bagaimana membangun benteng digital yang melindungi aset tanpa menghalangi inovasi.

---

## 🎯 Mengapa Kita Menggunakan Security & Identity? (The Why)
Sehebat apa pun arsitektur sebuah sistem, kegagalan keamanan dapat menghancurkan seluruh nilai bisnis:
1.  **Data Integrity**: Memastikan data tidak dimanipulasi oleh pihak yang tidak sah melalui hash dan enkripsi.
2.  **User Trust**: Melindungi identitas dan privasi pengguna adalah prasyarat mutlak untuk keberlanjutan produk.
3.  **Risk Mitigation**: Mengidentifikasi dan menutup celah keamanan (OWASP Top 10) sebelum dieksploitasi oleh aktor jahat.
4.  **Compliance & Governance**: Menjamin sistem mematuhi standar keamanan industri (seperti OAuth2/OIDC) dan kebijakan tata kelola identitas.

---

## 🧭 Visi Arsitektural: The Art of Digital Defense
Repositori ini membedah Keamanan melalui tiga lensa utama:
1. **Cryptography & Hashing**: Dasar-dasar perlindungan rahasia (Argon2, Salted Hashing, JWT).
2. **Identity Access Management (IAM)**: Protokol otentikasi dan otorisasi modern (OAuth 2.0, OpenID Connect).
3. **Application Security (AppSec)**: Taktik *Red/Blue Teaming* untuk mitigasi serangan siber (SQLi, XSS, CSRF).

## 🧬 Jalur Matriks: Matrix Cross-Path (The What)
Sesuai konstitusi `00-Mapping-Road`, hub ini adalah persilangan:
- **Sumbu-Y**: Semua Bahasa (Security Best Practices).
- **Sumbu-X**: RAK-08 (AI Orchestration) ➡️ **RAK-09 (Security & Identity Hub)** ➡️ Matrix Foundation.

Di sini kita belajar **"Bahwa seorang pemrogram senior menulis kode yang jalan, tapi seorang Insinyur Sistem Pakar menulis kode yang tidak bisa ditembus"**.

---

## 🏗️ Struktur 8-Rak (The Taxonomy)
1. **RAK-01: Anatomy & Landscape** (Security History, CIA Triad, Threat Modeling, Zero Trust Architecture).
2. **RAK-02: Foundation & Core Rules** (Authentication vs Authorization, Password Hashing: Salt, Peper, Argon2/Bcrypt).
3. **RAK-03: Evolution & Interfacing** (OAuth 2.0, OpenID Connect (OIDC), JWT Deep Dive: Header, Payload, Signature).
4. **RAK-04: Core Mechanics & Internals** (Cryptography: Symmetric vs Asymmetric, RSA, AES, Hashing Algorithms).
5. **RAK-05: Ecosystem & Tooling** (Identity Providers: Auth0, Keycloak; Security Tools: OWASP ZAP, Burp Suite).
6. **RAK-06: The Underworld** (Web Vulnerabilities: SQL Injection, XSS, CSRF, Session Hijacking, API Security).
7. **RAK-07: Specialization** (Infrastructure Security: SSL/TLS, Secrets Management (Vault), Rate Limiting, CORS).
8. **RAK-08: Matrix Intersection** (The Bridge: How Security protects RAK-01 Language Hubs and RAK-04 Storage Hubs).

---

## 📊 Status Proyek
Detail status per Rak dapat dilihat di [status.md](./status.md).

> [!NOTE]
> Proyek ini mengikuti standar dokumentasi **Gold Standard PPM V4**.

- `README.md` adalah pendahuluan ini.
- `docs/` berisi dokumentasi pendukung (pemetaan, aturan, referensi).
- `RAK-xx/` berisi semua rak utama.

## Dokumentasi
- [docs/root-governance.md](./docs/root-governance.md)