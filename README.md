# Awesome Localization [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Tools and APIs for localization teams, translators, and developers.

Browse products for translating content, publishing across languages, internationalizing applications, reviewing quality, maintaining language assets, and managing localization. Each entry is a named software or API product with a documented localization workflow. Each product appears once, under its main use.

[Suggest a tool or correction](https://github.com/ilyaspiridonov/awesome-localization/issues/new), or read the [contribution guide](contributing.md) for eligibility and evidence requirements. OSS labels link to the applicable open-source license.

## Contents

- [Translation Engines, APIs, and Models](#translation-engines-apis-and-models)
- [Subtitles, Dubbing, and Speech Translation](#subtitles-dubbing-and-speech-translation)
- [Website, CMS, and Commerce Localization](#website-cms-and-commerce-localization)
- [Internationalization Libraries and Developer Tools](#internationalization-libraries-and-developer-tools)
- [CAT Tools and Translation Editors](#cat-tools-and-translation-editors)
- [Human Translation and Post-Editing Tools and APIs](#human-translation-and-post-editing-tools-and-apis)
- [Quality Assurance and Localization Testing](#quality-assurance-and-localization-testing)
- [Terminology and Glossary Tools](#terminology-and-glossary-tools)
- [Translation Memory Management and Cleanup](#translation-memory-management-and-cleanup)
- [Translation Gateways and Model Routing](#translation-gateways-and-model-routing)
- [Translation Management and Collaboration](#translation-management-and-collaboration)

## Translation Engines, APIs, and Models

Products that generate translations from text or files, including cloud APIs and locally installed engines.

- [Amazon Translate](https://aws.amazon.com/translate/) - Cloud machine translation service. Translate text in real time or process document batches stored in Amazon S3.
- [Argos Translate](https://github.com/argosopentech/argos-translate) - Offline machine translation library and command-line tool ([OSS](https://github.com/argosopentech/argos-translate/blob/master/LICENSE)). Install language-pair model packages and translate locally from Python or the command line.
- [Azure Translator](https://azure.microsoft.com/en-us/products/ai-foundry/tools/translator) - Cloud text and document translation service. Use its APIs for translation and language detection, with custom models for domain-specific text.
- [DeepL API](https://www.deepl.com/en/products/api) - API for text and document translation. Integrate translation into applications and control terminology with glossaries.
- [Google Cloud Translation](https://cloud.google.com/translate) - Translation API with neural and translation LLM models. Choose models and apply glossaries through its Advanced edition.
- [Lara Translation API](https://developers.laratranslate.com/docs/translation-api) - Translation API with SDKs and REST access on request. Supply translation memories, glossaries, and surrounding context to adapt the output without training a custom model.

## Subtitles, Dubbing, and Speech Translation

Tools for translating timed text and spoken content, from subtitle editing to generated speech tracks.

- [ElevenLabs Dubbing](https://elevenlabs.io/docs/overview/capabilities/dubbing) - Audio and video dubbing tool with speaker detection. Generate translated speech tracks using the speakers' voice characteristics and retained background audio.
- [OOONA Tools](https://www.ooona.net/ooona-tools/) - Browser toolkit for caption and subtitle production. Translate timed source templates, check the target subtitles, and export standard timed-text formats.
- [Rask AI Video Translator](https://www.rask.ai/tools/video-translator) - Video translation and dubbing tool with editing for individual lines. Review the script, select cloned or preset voices, and export dubbed video or subtitles.
- [Subtitle Edit](https://github.com/SubtitleEdit/subtitleedit) - Subtitle editor with video preview and timing controls ([OSS](https://github.com/SubtitleEdit/subtitleedit/blob/main/LICENSE)). Translate, synchronize, and check subtitles alongside video and audio.
- [SubtitleNEXT](https://subtitlenext.com/product-line/individual/) - Timed-text software for audiovisual localization. Create multilingual captions, adjust timing, run error checks, and export professional subtitle formats.

## Website, CMS, and Commerce Localization

Products for translating site and store content and publishing multilingual versions, with tools for editing translations in context.

- [ConveyThis](https://www.conveythis.com/) - Website translation platform with language-specific URLs and translation controls. Translate pages automatically, then edit text in a visual editor and maintain terminology with a glossary.
- [Linguise](https://www.linguise.com/) - Website translation platform with CMS and store integrations. Connect a supported site builder or commerce system and refine translations through its dashboard or visual editor.
- [TranslatePress](https://translatepress.com/) - WordPress translation plugin with a visual editor. Translate pages in context, including forms, page-builder output, and WooCommerce content.
- [Weglot](https://www.weglot.com/features) - Website translation platform with visual editing and multilingual SEO controls. Publish translated pages with language-specific URLs and hreflang tags, then refine the wording in context.
- [WPML](https://wpml.org/) - WordPress multilingual plugin with site and store translation workflows. Translate posts and interface strings, and localize WooCommerce products with its commerce add-on.

## Internationalization Libraries and Developer Tools

Libraries and tools for extracting application messages, handling plurals, formatting locale-specific data, and loading translations.

- [Babel (Python)](https://babel.pocoo.org/en/stable/intro.html) - Internationalization utilities for Python applications ([OSS](https://github.com/python-babel/babel/blob/master/LICENSE)). Extract messages from source and templates, manage gettext catalogs, and format dates and numbers using locale data.
- [Fluent](https://projectfluent.org/) - Localization system with JavaScript, Python, and Rust implementations ([OSS](https://github.com/projectfluent/fluent.js/blob/main/LICENSE)). Define language-specific plural, gender, and case variants independently of other locales.
- [GNU gettext](https://www.gnu.org/software/gettext/) - Internationalization toolkit with [GPL tools](https://www.gnu.org/software/gettext/manual/html_node/GNU-GPL.html) and [LGPL runtime libraries](https://www.gnu.org/software/gettext/manual/html_node/GNU-LGPL.html). Extract translatable strings, merge updates into PO catalogs, and compile translations for application use.
- [i18next](https://www.i18next.com/) - JavaScript internationalization framework ([OSS](https://github.com/i18next/i18next/blob/master/LICENSE)). Organize translations into namespaces, load them on demand, and render messages with interpolation and plural forms.
- [ICU](https://icu.unicode.org/) - Internationalization libraries for C/C++ and Java ([OSS](https://github.com/unicode-org/icu/blob/main/LICENSE)). Format messages, dates, numbers, and currencies using locale rules.
- [Lingui](https://lingui.dev/introduction) - Internationalization library and CLI for JavaScript and TypeScript ([OSS](https://github.com/lingui/js-lingui/blob/main/LICENSE)). Extract messages from source code into PO catalogs and compile completed translations into runtime modules.
- [next-intl](https://next-intl.dev/) - Internationalization library for Next.js ([OSS](https://github.com/amannn/next-intl/blob/main/LICENSE)). Translate messages in server and client components and publish localized routes with translated pathnames.
- [Paraglide JS](https://paraglidejs.com/) - Compiler-based internationalization library for JavaScript and TypeScript ([OSS](https://github.com/opral/paraglide-js/blob/main/LICENSE)). Compile messages into typed functions so bundlers can remove unused translations.

## CAT Tools and Translation Editors

Computer-assisted translation workspaces for working through bilingual content with memories, terminology, and reference material.

- [CafeTran Espresso](https://www.cafetran.com/) - CAT tool for Windows, macOS, and Linux. Work with bilingual files and packages from other CAT tools while reusing translation memories.
- [memoQ translator pro](https://www.memoq.com/product/memoq-translator-pro/) - Windows CAT tool for professional translators. Reuse translation memory with context matching and align reference documents with LiveDocs.
- [OmegaT](https://omegat.org/) - Desktop translation memory tool ([OSS](https://sourceforge.net/p/omegat/code/ci/master/tree/release/OmegaT-license.txt?format=raw)). Translate projects containing multiple files with fuzzy matching and TMX memory exchange.
- [Trados Studio](https://www.trados.com/product/studio/) - Desktop CAT application with an included cloud browser editor. Translate and review content using translation memories and terminology, then move supported projects between desktop and cloud.

## Human Translation and Post-Editing Tools and APIs

Products for requesting human proofreading, post-editing, or translation through a software workflow and receiving the completed work. The tasks available differ by product; a human translation API does not automatically accept existing translations for proofreading.

- [Gengo API](https://developers.gengo.com/overview/) - API for requesting human translation from an application. Submit text, receive completed translations by callback, and approve or request revisions through the review workflow.
- [LILT Verify](https://lilt.com/products/expert-human-verifiers) - Human verification workflow within LILT's translation platform. Route selected translations to specialist linguists to review meaning, tone, and terminology.
- [TextMaster API](https://developer.textmaster.com/) - API for translation and proofreading projects. Submit text or files for proofreading and receive status updates through callbacks.
- [Unbabel LangOps Platform](https://unbabel.com/product/) - Translation platform with quality estimation and optional human review. Route translations for editor review and return the results to connected content or customer support systems.

## Quality Assurance and Localization Testing

Tools for finding linguistic errors, checking consistency, and reviewing translations in product context.

- [lexiQA](https://lexiqa.net/) - Linguistic QA service with an API and CAT integrations. Check translated text as it is written against rules for spelling, terminology, formatting, and consistency with the source.
- [LocalyzerQA](https://lingoport.com/software-localization-tools/localyzerqa-lqa/) - Linguistic review tool for localized applications. Navigate the application, select text on screen, and submit a corrected translation with the interface context visible.
- [Verifika](https://e-verifika.com/) - QA application for bilingual translation files. Detect formatting, consistency, terminology, spelling, and number issues, then review and correct them in its editor.
- [Xbench](https://www.xbench.net/) - Desktop translation QA and terminology checker. Load CAT files, run selected QA checks or reusable checklists, and export issue reports.

## Terminology and Glossary Tools

Products for extracting candidate terms, maintaining multilingual termbases, and making approved wording available during translation.

- [Anchovy](https://maxprograms.com/products/anchovy.html) - Glossary editor and term extractor with [OSS](https://github.com/maxprograms-com/Anchovy/blob/main/LICENSE) source and subscription installers. Extract term candidates from documents and exchange glossaries in TBX, TMX, CSV, or Excel formats.
- [MultiTerm](https://www.trados.com/product/multiterm/) - Multilingual terminology management application. Attach definitions and context to terms and reuse approved terminology in Trados Studio.
- [OneClick Terms](https://terms.sketchengine.eu/) - Terminology extraction tool from Sketch Engine. Extract monolingual or bilingual candidate terms from documents and translation memories, then review and export selected terms.

## Translation Memory Management and Cleanup

Dedicated tools and plugins for inspecting, correcting, and consolidating reusable translation segments.

- [TM Cleaner](https://store.crowdin.com/tm_cleaner_app) - Crowdin app for removing duplicate translation memory records. Select a memory in your Crowdin account and deduplicate its segments while retaining a backup of the original records.
- [TMXEditor](https://maxprograms.com/products/tmxeditor.html) - Desktop TMX editor with [OSS](https://github.com/maxprograms-com/TMXEditor/blob/master/LICENSE) source and subscription installers. Edit, validate, merge, and split multilingual translation memories.
- [Transept TMX Cleaner](https://transept.ai/tools/tmx-cleaner) - TMX cleanup and conversion tool that processes files locally in your browser. Remove exact duplicates and empty entries, or export a memory to a spreadsheet and rebuild it after editing.

## Translation Gateways and Model Routing

Products for connecting engines and choosing which provider handles a translation request or job.

- [Custom.MT Platform](https://custom.mt/custom-machine-translation-platform/) - Machine translation hub with templates for multiple engines. Choose engines for language and domain needs and configure backup engines for continuity.
- [Intento Language Hub](https://inten.to/enterprise-language-hub/) - Translation platform with configurable engine routing tables. Route requests by language pair to primary and backup providers through one translation integration.
- [Phrase Language AI](https://support.phrase.com/hc/en-us/articles/5709660879516-Phrase-Language-AI-Machine-Translation-in-Phrase) - MT routing hub for Phrase products and API workflows. Configure MT profiles and use MT Autoselect to select engines by language pair and, for supported source languages, content domain.

## Translation Management and Collaboration

Platforms for coordinating source content, translators, reviewers, and delivery across projects.

- [Crowdin](https://crowdin.com/) - Localization management platform for software and content. Sync source files with Git repositories and return completed translations through pull requests.
- [Lokalise Expert](https://docs.lokalise.com/en/articles/1400427-what-is-lokalise) - Localization management platform for software teams. Attach screenshots to translation keys on Growth plans and above so translators can see where strings appear.
- [Phrase TMS](https://phrase.com/platform/tms/) - Cloud translation management system for content and file workflows. Assign jobs across vendors and track reviews, translation memories, and terminology in one workspace.
- [Smartcat](https://www.smartcat.com/translation-management-system/) - Translation management platform with a linguist marketplace. Organize projects, assign reviewers, and manage linguist contracting and payments in the platform.
- [Tolgee](https://tolgee.io/) - Localization platform with an [Apache-2.0-licensed core](https://github.com/tolgee/tolgee-platform/blob/main/LICENSE) and proprietary enterprise modules. Edit strings in app context and attach screenshots for translators.
- [Weblate](https://weblate.org/en/) - Continuous localization platform with version control integration ([OSS](https://github.com/WeblateOrg/weblate/blob/main/LICENSE)). Pull translation files from a repository and commit completed translations back to it.

## Footnotes

Maintained by Ilya Spiridonov. Community contributions are welcome.

Sections and descriptions evolve through contributions to this repository.
