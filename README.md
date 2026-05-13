# QA Portfolio

Repo ini digunakan sebagai portfolio khusus QA untuk menggabungkan artefak dari
repo lain dan menyimpan file-file QA dalam satu tempat.

## Tujuan

- Menjadi pusat portfolio QA
- Mengumpulkan hasil kerja dari berbagai project/repo
- Menyimpan dokumen dan bukti testing agar mudah ditinjau

## Isi portfolio

Portfolio ini dapat berisi:

- link ke repo/project yang pernah dikerjakan
- test plan
- test case
- checklist pengujian
- bug report
- hasil API testing
- automation script
- screenshot atau evidence testing

## Struktur yang disarankan

```text
qa-portfolio/
├── README.md
├── manual-testing/
├── api-testing/
├── automation/
├── bug-reports/
└── evidence/
```

## Daftar project QA

| Project/Repo                                                                          | Jenis Pengujian   | Tech Stack  | Artefak                               |
| ------------------------------------------------------------------------------------- | ----------------- | ----------- | ------------------------------------- |
| [Playwright-Tutorial-Indo](https://github.com/nopevbf/Playwright-Tutorial-Indo)       | Automation        | TypeScript  | Test scripts, automation framework    |
| [Android Automation](https://github.com/nopevbf/android-automation)                   | Mobile Automation | HTML/Mobile | Mobile test automation, test cases    |
| [Robotframework-Basic](https://github.com/nopevbf/Robotframework-Basic)               | Automation        | Python      | Robot Framework scripts, test suites  |
| [Selenium UI Testing Java](https://github.com/nopevbf/Selenium-UI-Testing-Java)       | UI Testing        | Java        | Selenium test cases, test reports     |
| [Quality Assurance SkillTest](https://github.com/nopevbf/Quality-Assurance-SkillTest) | Testing           | Java        | QA test cases, test execution results |

## Daftar Artefak QA

### Manual Testing

- [Test Cases - Camera Feature](manual-testing/TestCase_Camera.md): 36 test cases untuk fitur kamera (Functional Testing + Complete Test Coverage)
- [Test Case Document (PDF)](manual-testing/Testcase%20[Camera].pdf): Original test case PDF

### Bug Reports

- [Bug Report - Online Store](bug-reports/BugReport_OnlineStore.md): 16 bug reports untuk Demoblaze e-commerce website
  - 2 Critical, 10 High Priority, 4 Medium Priority
  - Coverage: Navbar, Contact Form, Checkout, Payment, Cart, Pagination, Footer, Category Filter

## Cara pakai repo ini

1. Tambahkan folder atau file QA sesuai project yang ingin ditampilkan.
2. Simpan artefak QA dari repo lain ke dalam folder yang relevan.
3. Perbarui tabel project agar portfolio mudah dibaca reviewer.
4. Konversi dokumen Excel ke format Markdown untuk kemudahan akses dan versioning.
