# open-source-ai-contribution-policies

A list of policies by different open source projects about how to engage with AI-generated contributions.

**Feel free to submit Pull Requests with policies you find in other projects!**

## Similar projects

- For a similar overview with plots and more statistics, check out this excellent article by Kate Holterhoff: [The Generative AI Policy Landscape in Open Source](https://redmonk.com/kholterhoff/2026/02/26/generative-ai-policy-landscape-in-open-source/)
- The CHAOSS Working Group on AI Alignment also keeps a list here: https://github.com/chaoss/wg-ai-alignment/tree/main/moderation
- A list of software that has taken steps to reject AI in its development processes: https://codeberg.org/brib/slopfree-software-index

## Policies

Project | Policy link | AI? | Disclosure required | Copyright statement | Human in the loop | Notes
--- | --- | --- | --- | --- | --- | ---
[Adwaita](https://gitlab.gnome.org/GNOME/libadwaita) | [Use of Generative AI](https://gitlab.gnome.org/GNOME/libadwaita/-/blob/main/CONTRIBUTING.md?ref_type=heads#use-of-generative-ai) | No | - | - | - |
[Alacritty](https://github.com/alacritty/alacritty) | [LLM/"AI" Contributions](https://github.com/alacritty/alacritty/blob/master/CONTRIBUTING.md#llmai-contributions) | No | - | - | - |
[Apache Airflow](https://airflow.apache.org/) | [Gen-AI Assisted contributions](https://github.com/apache/airflow/blob/main/contributing-docs/05_pull_requests.rst#gen-ai-assisted-contributions) | Yes | Yes | Yes | Yes | [Add Copilot code review instructions to catch AI-slop PRs#62442](https://github.com/apache/airflow/pull/62442)
[Apache CouchDB](https://couchdb.apache.org) | [Contribution Guidelines](https://github.com/apache/couchdb/blob/main/CONTRIBUTING.md#artificial-intelligence-and-large-language-models-contributions-policy) | No | - | - | - |
[Apache DataFusion](https://datafusion.apache.org) | [AI-Assisted contributions](https://datafusion.apache.org/contributor-guide/index.html#ai-assisted-contributions) | Yes | No | No | Yes | [Better ways to contribute than an AI dump](https://datafusion.apache.org/contributor-guide/index.html#better-ways-to-contribute-than-an-ai-dump)
[Apache Kvrocks](https://kvrocks.apache.org/) | [Guidelines for AI-assisted Contributions](https://kvrocks.apache.org/community/contributing/#guidelines-for-ai-assisted-contributions) | Yes | Yes | Yes | Yes |
[Apache PouchDB](https://pouchdb.com) | [Contribution Guidelines](https://github.com/apache/pouchdb/blob/master/CONTRIBUTING.md#artificial-intelligence-and-large-language-models-contributions-policy) | No | - | - | - |
[Apache® Software Foundation (ASF)](https://www.apache.org/) | [ASF Generative Tooling Guidance](https://www.apache.org/legal/generative-tooling.html) | Yes | Yes | Yes | - | Applies to all ASF projects, but enforcement is decentralized. Requires use of "Generated-by:" in commit message.
[Arrow](https://arrow.apache.org) | [AI-generated code](https://arrow.apache.org/docs/dev/developers/overview.html#ai-generated-code) | Yes | Yes | Yes | Yes |
[Asahi Linux](https://asahilinux.org): | [Generative AI](https://asahilinux.org/docs/project/policies/slop/) | No | - | - | - |
[Astropy](https://www.astropy.org/) | [Usage of Generative AI](https://github.com/astropy/astropy-project/blob/main/policies/ai-policy.md) | Yes | No | No | Yes |
[attrs](https://github.com/python-attrs/attrs) | [Generative AI/LLM Policy](https://github.com/python-attrs/attrs/blob/main/.github/AI_POLICY.md)| Yes | ? | Yes | Yes | "No LLM bots in Co-authored-by:s."
[CapyPDF](https://github.com/jpakkane/capypdf) | [AI Policy](https://github.com/jpakkane/capypdf/?tab=readme-ov-file#ai-policy) | No | - | - | - |
[Cataclysm: Dark Days Ahead](http://cataclysmdda.org/) | [CONTRIBUTING.md](https://github.com/CleverRaven/Cataclysm-DDA/blob/master/CONTRIBUTING.md#licensing-and-authorship) | No | - | - | - |
[CCExtractor](https://ccextractor.org/) | [Using AI to generate PRs before and during GSoC](https://ccextractor.org/public/gsoc/ai_policy/) | Yes | Yes | Yes | Yes | Mark PRs as "AI-generated/AI-assisted/No AI used"
[CC Open Source](https://opensource.creativecommons.org/) | [Contribution Guidelines](https://opensource.creativecommons.org/contributing-code/) | No | - | - | - |
[Clojure](https://clojure.org) | [No Generated Code](https://clojure.org/dev/contributor_agreement#_no_generated_code) | No | - | - | - |
[CloudNativePG](https://cloudnative-pg.io/) | [AI Policy](https://github.com/cloudnative-pg/governance/blob/main/AI_POLICY.md) | Yes | Yes | Yes | Yes |
[conda](https://github.com/conda/conda) | [Generative AI policy](https://docs.conda.io/projects/conda/en/latest/dev-guide/contributing.html#generative-ai) | Yes | No | Yes | Yes |
[CPython](https://github.com/python/cpython) | [Generative AI policy](https://devguide.python.org/getting-started/generative-ai/) | Yes | No | No | Yes | "Disclosure of the use of AI tools in the PR description is appreciated, while not required."
[CuPy](https://cupy.dev) | [AI Policies](https://docs.cupy.dev/en/stable/contribution.html#ai-policies) | Yes | No | No | Yes |
[curl](https://curl.se/) | [On AI Use in CURL](https://curl.se/dev/contribute.html#on-ai-use-in-curl) | Yes | Yes | Yes | Yes | "The golden rule is that a contribution should be worth more to the project than the time it takes to review it, which is usually not the case if large parts of your PR were written by LLMs."
[cilium](https://cilium.io/) | [Cilium Generative AI Policy](https://github.com/cilium/community/blob/main/AI-POLICY.md) | Yes | Yes | Yes | Yes | DCO signoff required for all contributions, including AI-generated ones.
[DataJourneyHQ](https://datajourneyhq.com/) | [AI aware checklist](https://github.com/DataJourneyHQ/DataJourney/wiki/Contribution-Guidelines-(AI%E2%80%90Aware)) | Yes | Yes | No | - |
[Django](https://www.djangoproject.com/) | [AI-Assisted Contributions](https://docs.djangoproject.com/en/dev/internals/contributing/writing-code/submitting-patches/#ai-assisted-contributions) | Yes | Yes | No | Yes | [PR template](https://github.com/django/django/blob/main/.github/pull_request_template.md); No automated AI reviews
[dlt](https://dlthub.com/) | [Blog post (No policy; proactively encourages AI usage)](https://blog.probabl.ai/how-you-can-embrace-ai-in-your-open-source-projects-contribution-cycle-insights-from-dlt) | Yes | No | No | No |
[Drupal](https://www.drupal.org) | [Policy on the use of AI when contributing to Drupal](https://www.drupal.org/docs/develop/issues/issue-procedures-and-etiquette/policy-on-the-use-of-ai-when-contributing-to-drupal) | Yes | Yes | Yes | Yes |
[do](https://codeberg.org/cgranade/do) | [License and AI Policy](https://codeberg.org/cgranade/do#license-and-ai-policy) | No | - | - | - | - |
[Dune 3D](https://dune3d.org/) | [Use of large language models / generative "AI"](https://github.com/dune3d/dune3d/blob/main/CONTRIBUTING.md#use-of-large-language-models--generative-ai) | No | - | - | - | - |
[EasyBuild](https://easybuild.io/) | [EasyBuild AI Policy](https://docs.easybuild.io/policies/ai/) | Yes | Yes | No | Yes | Requires declaration of specific AI models/tools used.
[Elastic](https://gitlab.gnome.org/World/elastic) | [Use of Generative AI](https://gitlab.gnome.org/World/elastic#use-of-generative-ai) | No | - | - | - | - |
[Elementary OS](https://elementary.io/) | [Generative AI Policy](https://docs.elementary.io/contributor-guide/development/generative-ai-policy) | No | - | - | - | - |
[FastAPI](https://fastapi.tiangolo.com) | [Automated Code and AI](https://tiangolo.com/open-source/contributing/#automated-code-and-ai) | Yes | No | No | Yes | "If the human effort put in a PR, e.g. writing LLM prompts, is less than the effort we would need to put to review it, please don't submit the PR."
[Firefox](https://github.com/mozilla-firefox/firefox) | [Firefox AI Coding Policy](https://firefox-source-docs.mozilla.org/contributing/ai-coding.html) | Yes | No | No | Yes |
[Flutter](https://flutter.dev/) | [AI contribution guidelines](https://github.com/flutter/flutter/blob/master/docs/contributing/Tree-hygiene.md#ai-contribution-guidelines) | Yes | No | No | Yes |
[Forgejo](https://forgejo.org/) | [AI Agreement](https://codeberg.org/forgejo/governance/src/branch/main/AIAgreement.md) | No | - | - | - | - |
[GDAL](https://gdal.org/) | [AI/LLM tool policy](https://gdal.org/en/stable/community/ai_tool_policy.html) | Yes | Yes | Yes | Yes |
[Gedit](https://gedit-text-editor.org/) | [Gedit Development Guidelines - No Large Language Models AI tools](https://gitlab.gnome.org/World/gedit/gedit/-/blob/master/docs/guidelines/no-llm-tools.md) | No | - | - | - | - |
[Gentoo Linux](https://www.gentoo.org/) | [AI Policy](https://wiki.gentoo.org/wiki/Project:Council/AI_policy) | No | - | - | - | - |
[Ghostty](https://ghostty.org/) | [AI Usage Policy](https://github.com/ghostty-org/ghostty/blob/main/AI_POLICY.md) | Yes | Yes | No | Yes | "Our reason for the strict AI policy is not due to an anti-AI stance, but instead due to the number of highly unqualified people using AI."
[GIMP](https://gitlab.gnome.org/GNOME/gimp) | [Contribution Guidelines](https://gitlab.gnome.org/GNOME/gimp/-/blob/master/.gitlab/merge_request_templates/default.md?plain=1#L11-12) | No | - | - | - | - |
[Gitea](https://gitea.com/) | [AI Contribution Policy](https://github.com/go-gitea/gitea/blob/main/CONTRIBUTING.md#ai-contribution-policy) | Yes | Yes | No | Yes |
[Glasgow Interface Explorer](https://glasgow-embedded.org) | [Contributing code or documentation](https://glasgow-embedded.org/latest/contribute.html#contributing-code-or-documentation) | No | - | - | - | - |
[GNOME Extensions](https://gjs.guide/extensions/development/creating.html)| [Review Guidelines](https://gjs.guide/extensions/review-guidelines/review-guidelines.html#extensions-must-not-be-ai-generated) | Yes | - | - | Yes | "While it is not prohibited to use AI as a learning aid or a development tool (i.e. code completions), extension developers should be able to justify and explain the code they submit, within reason."
[GNU Binutils](https://sourceware.org/binutils/) | [LLM Generated Content](https://sourceware.org/binutils/wiki/LLM_Generated_Content) | No | - | - | - | - |
[goose](https://github.com/aaif-goose/goose) | [How to Use AI with goose](https://github.com/block/goose/blob/main/HOWTOAI.md) | Yes | No | No | Yes | [AGENTS.md file](https://github.com/aaif-goose/goose/blob/main/AGENTS.md)
[GoToSocial](https://gotosocial.org/) | [Code of Conduct](https://codeberg.org/superseriousbusiness/gotosocial/src/branch/main/CODE_OF_CONDUCT.md) | No | - | - | - | - |
[Homebrew](https://github.com/Homebrew/brew/tree/main) | [(AI/LLM) usage](https://github.com/Homebrew/brew/blob/main/CONTRIBUTING.md#artificial-intelligencelarge-language-model-aillm-usage) | Yes | Yes | No | Yes | Disclose model/tool and only one AI-assisted PR open at a time.
[Icechunk](https://icechunk.io/en/latest/) | [AI Usage/Contribution Policy](https://icechunk.io/en/latest/ai-policy/) | Yes | No | No | Yes |
[IREE (Intermediate Representation Execution Environment)](https://iree.dev/) | [AI tool use](https://iree.dev/developers/general/contributing/#ai-tool-use) | Yes | Yes | Yes | Yes | Use "Assisted-by:" or "Co-authored-by:"
[Jellyfin](https://jellyfin.org/) | [Jellyfin LLM/"AI" Development Policy](https://jellyfin.org/docs/general/contributing/llm-policies/) | Yes | No | No | Yes |
[Joomla](https://www.joomla.org/) | [Generative AI policy](https://developer.joomla.org/generative-ai-policy.html) | Yes | Yes | Yes | Yes |
[Kornia](https://github.com/kornia/kornia/tree/main) | [AI_POLICY.md](https://github.com/kornia/kornia/blob/main/AI_POLICY.md) | Yes | Yes | No | Yes | Use "AI-generated/AI-assisted/No AI" labels
[Krita](https://krita.org) | [AI Moratorium](https://invent.kde.org/graphics/krita#user-content-ai-moratorium) | No | - | - | - | [maintainer statement](https://krita-artists.org/t/policy-on-llm-code/178248/12), to be reviewed in October 2026
[Kubernetes](https://kubernetes.io/) | [AI Guidance](https://www.kubernetes.dev/docs/guide/pull-requests/#ai-guidance) | Yes | Yes | No | Yes | "Assisted-by:", "Co-developed-by:" not allowed
[LinkML](https://linkml.io/) | [AI Covenant](https://github.com/linkml/linkml/blob/main/AI_COVENANT.md) | Yes | Yes* | No | Yes | No co-authorship with AI tools allowed; disclose usage when you don't understand the proposed changes fully
[Linux Kernel](https://kernel.org/) | [AI Coding Assistants](https://kernel.org/doc/html/next/process/coding-assistants.html) | Yes | Yes | Yes | Yes | "Assisted-by:" required; DCO required.
[LLVM](https://llvm.org) | [LLVM AI Tool Use Policy](https://llvm.org/docs//AIToolPolicy.html) | Yes | Yes | Yes | Yes | "Using AI tools to fix issues labelled as “good first issues” is forbidden."
[libmanette](https://gitlab.gnome.org/GNOME/libmanette) | [Use of Generative AI](https://gitlab.gnome.org/GNOME/libmanette/-/blob/main/CONTRIBUTING.md?ref_type=heads#use-of-generative-ai) | No | - | - | - |
[LÖVE](https://love2d.org/) | [Contributing](https://github.com/love2d/love#contributing) | No | - | - | - |
[GNOME Loupe](https://welcome.gnome.org/app/Loupe/) | [Use of Generative AI](https://gitlab.gnome.org/GNOME/loupe/-/blob/main/CONTRIBUTING.md?ref_type=heads#use-of-generative-ai) | No | - | - | - |
[Linux man-pages](http://www.kernel.org/doc/man-pages/) | [AI - artificial intelligence policy](https://git.kernel.org/pub/scm/docs/man-pages/man-pages.git/tree/CONTRIBUTING.d/ai) | No | - | - | - |
[Matplotlib](https://matplotlib.org) | [Restrictions on Generative AI Usage](https://matplotlib.org/devdocs/devel/contribute.html#generative-ai) | Yes | Yes | No | Yes | "AI Disclosure" secion in [PR template](https://github.com/matplotlib/matplotlib/blob/main/.github/PULL_REQUEST_TEMPLATE.md) must be filled
[Mesa](https://mesa3d.org/) | [Submitting Patches](https://gitlab.freedesktop.org/mesa/mesa/-/blob/main/docs/submittingpatches.rst?ref_type=heads#id2) | Yes | Yes | Yes | Yes | Use "Assisted-by:" or "Generated-by:"; do not use "Co-authored-by:" with AI tools.
[MicroPython](https://micropython.org) | [Generative AI Policy](https://github.com/micropython/micropython/wiki/ContributorGuidelines#generative-ai-policy) | Yes | No | No | Yes |
[MDAnalysis](https://www.mdanalysis.org/) | [MDAnalysis AI-generated contributions policy](https://github.com/MDAnalysis/mdanalysis/blob/develop/AI_POLICY.md) | Yes* | Yes | No | Yes | No "substantial" contributions generated by AI tools.
[Molecular Nodes](https://bradyajohnston.github.io/MolecularNodes/) | [MolecularNodes AI-generated contributions policy](https://github.com/BradyAJohnston/MolecularNodes/blob/main/AI_POLICY.md) | Yes* | Yes | No | Yes | No "substantial" contributions generated by AI tools.
[napari](https://napari.org) | [AI use policy and guidelines](https://napari.org/dev/developers/contributing/ai.html) | Yes | Yes | No | Yes |
[NetBSD](https://www.netbsd.org/) | [NetBSD Commit Guidelines](https://www.netbsd.org/developers/commit-guidelines.html) | Yes* | Yes | No | No | AI-assisted contributions require explicit core approval
[NumPy](https://numpy.org) | [AI Policy](https://numpy.org/devdocs/dev/ai_policy.html) | Yes | Yes | Yes | Yes | [Mailing list discussion](https://mail.python.org/archives/list/numpy-discussion@python.org/thread/LAR7P3KQWHWAIKYSHTS2MY7X4HUBVA3L/)
[nvim-tree](https://github.com/nvim-tree/nvim-tree.lua) | [AI Usage Policy: Highly Discouraged](https://github.com/nvim-tree/nvim-tree.lua?tab=contributing-ov-file#ai-usage-policy-highly-discouraged) | Yes* | Yes | No | Yes | "AI generated code is discouraged as this doesn't match (these) nvim-tree values.""
[OCaml](https://github.com/ocaml/ocaml) | [Guidelines relevant to AI-assisted contributions](https://github.com/ocaml/ocaml/blob/trunk/AI.md) | Yes | Yes | Yes | Yes |
[OpenInfra](https://openinfra.org/) | [Policy for AI Generated Content](https://openinfra.org/legal/ai-policy) | Yes | Yes | Yes | Yes | Required use of "Assisted-by:" or "Generated-by:". Open Source AI models recommended.
[Oxide](https://oxide.computer/) | [Using LLMs at Oxide](https://rfd.shared.oxide.computer/rfd/0576) | Yes | - | No | Yes | Comprehensive, extensive policy.
[Open edX](https://openedx.org/) | [AI Contribution Policy](https://github.com/openedx/.github/blob/master/AI_POLICY.md) | Yes* | Yes | No | Yes | Only specific tools with a "sufficient reputation for proper training" are allowed.
[OpenJDK](https://openjdk.org/) | [OpenJDK Interim Policy on Generative AI](https://openjdk.org/legal/ai) | No | - | - | - | Interim policy.
[Pandas](https://pandas.pydata.org) | [Automated contributions policy](https://pandas.pydata.org/docs/dev/development/contributing.html#automated-contributions-policy) | Yes | Yes | No | Yes |
[pgwatch](https://pgwat.ch/) | [ARTIFICIAL INTELLIGENCE & AUTOMATION POLICY (V1.0)](https://github.com/cybertec-postgresql/pgwatch/blob/master/AI_POLICY.md) | Yes | Yes | No | Yes | Must mention specific tools used.
[pip](https://github.com/pypa/pip) | [Generative AI/LLM Policy](https://github.com/pypa/pip/blob/main/AI_POLICY.md) | Yes | No | Yes | Yes | No "Co-authored-by:" with AI tools.
[pip-tools](https://pip-tools.readthedocs.io) | [LLM Generated Contributions](https://pip-tools.readthedocs.io/en/latest/contributing/#project-contribution-guidelines) | Yes | No | No | Yes |
[Polars](https://pola.rs/) | [AI Usage Policy](https://github.com/pola-rs/polars/blob/8425c750b9c5d28c79428998fda2320d076d4178/AI_POLICY.md) | Yes | Yes | No | Yes |
[Processing/p5.js](https://processing.org/) | [AI Usage Policy](https://github.com/processing/processing4/blob/main/AI_USAGE_POLICY.md) | Yes | Yes | No | Yes | Disclose specific tools used.
[Pytest](https://docs.pytest.org/en/stable/) | [AI/LLM-Assisted Contributions Policy](https://github.com/pytest-dev/pytest/blob/main/CONTRIBUTING.rst#aillm-assisted-contributions-policy) | Yes | No | No | Yes | Recommended use of "Co-authored-by:".
[PyTorch](https://pytorch.org/) | [AI-Assisted Development](https://github.com/pytorch/pytorch/blob/main/CONTRIBUTING.md#ai-assisted-development) | Yes | No | No | Yes |
[PyVista](https://pyvista.org) | [Generative AI](https://github.com/pyvista/pyvista/blob/main/CONTRIBUTING.rst#generative-ai) | Yes | No | No | Yes | Follows CPython's policy.
[postmarketOS](https://postmarketos.org) | [AI Policy](https://docs.postmarketos.org/policies-and-processes/development/ai-policy.html) | No | - | - | - | - |
[qutip](https://qutip.org/) | [AI Tools Usage Policy](https://github.com/qutip/qutip/blob/master/CONTRIBUTING.md#ai-tools-usage-policy) | Yes | Yes | Yes | Yes | No AI contributions to "good first issues".
[QEMU](https://www.qemu.org) | [Use of AI-generated content](https://www.qemu.org/docs/master/devel/code-provenance.html#use-of-ai-generated-content) | No | - | - | - | - |
[QGIS](https://qgis.org/) | [QGIS Enhancement: AI tool use policy](https://github.com/qgis/QGIS-Enhancement-Proposals/blob/master/qep-408-ai-tool-policy.md) | Yes | Yes | Yes | Yes | Use "Assisted-by:" or "Generated-by:" labels.
[Requests](https://requests.readthedocs.io/en/latest/) | [Generative AI/LLM Policy](https://github.com/psf/requests/blob/main/.github/AI_POLICY.md) | Yes | No | Yes | Yes | No "Co-authored-by:" with AI tools.
[ruff](https://github.com/astral-sh/ruff) | [AI Policy](https://github.com/astral-sh/.github/blob/main/AI_POLICY.md) | Yes | No | No | Yes |
[Redox OS](https://www.redox-os.org/) | [AI Policy](https://gitlab.redox-os.org/redox-os/redox/-/blob/master/CONTRIBUTING.md#ai-policy) | No | - | - | - | - |
[SearXNG](https://docs.searxng.org) | [AI Policy](https://github.com/searxng/searxng/blob/master/AI_POLICY.rst) | Yes | Yes | No | Yes |
[SciActive](https://sciactive.com) | [Human Contribution Policy](https://sciactive.com/human-contribution-policy/) | No | - | - | - | - |
[scikit-image](https://scikit-image.org/) | [AI Policy](https://scikit-image.org/docs/dev/development/contribute.html#ai-policy) | Yes | Yes | No | Yes |
[scikit-learn](https://scikit-learn.org) | [Automated Contributions Policy](https://scikit-learn.org/dev/developers/contributing.html#automated-contributions-policy) | Yes | Yes | No | Yes |
[SciPy](https://scipy.org) | [AI Policy](https://scipy.github.io/devdocs/dev/conduct/ai_policy.html) | Yes | Yes | Yes | Yes |
[SDL](https://libsdl.org/) | [AGENTS.md](https://github.com/libsdl-org/SDL/blob/main/AGENTS.md) | No | - | - | - | AI may be used to identify issues, but solutions must be authored by humans. [PR template](https://github.com/libsdl-org/SDL/blob/main/.github/PULL_REQUEST_TEMPLATE.md) asks contributors to confirm authorship.
[SDL_net](https://github.com/libsdl-org/SDL_net) | [AGENTS.md](https://github.com/libsdl-org/SDL_net/blob/main/AGENTS.md) | No | - | - | - | Same policy as SDL.
[Servo](https://servo.org) | [AI Contributions](https://book.servo.org/contributing/getting-started.html#ai-contributions) | No | - | - | - |
[Sphinx](https://www.sphinx-doc.org/en/master/) | [AI Policy](https://github.com/sphinx-doc/sphinx/blob/master/doc/internals/ai-policy.rst) | Yes | Yes | Yes | Yes | - |
[stb](https://github.com/nothings/stb) | [AI AND LLM ARE FORBIDDEN](https://github.com/nothings/stb/blob/master/CONTRIBUTING.md#ai-and-llm-are-forbidden) | No | - | - | - |
[STAC](https://stacspec.org/) | [AI/LLM tool policy](https://github.com/stac-utils/stac-utils.github.io/blob/main/docs/ai-contribution-policy.md) | Yes | Yes | No | Yes | Use "Assisted-by:" and similar labels.
[SymPy](https://www.sympy.org) | [AI Generated Code and Communication Policy](https://docs.sympy.org/dev/contributing/ai-generated-code-policy.html) | Yes | Yes | Yes | Yes |
[Telegraf](https://influxdata.com/telegraf) | [AI Generated Code](https://github.com/influxdata/telegraf?tab=contributing-ov-file#ai-generated-code) | No | - | - | - | - |
[TorchGeo](https://torchgeo.org/) | [AI Policy](https://github.com/torchgeo/governance/blob/main/AI-POLICY.md) | Yes | Yes | Yes | Yes | - |
[ty](https://github.com/astral-sh/ty) | [AI Policy](https://github.com/astral-sh/.github/blob/main/AI_POLICY.md) | Yes | No | No | Yes |
[typescript-eslint](https://typescript-eslint.io/) | [AI Contribution Policy](https://typescript-eslint.io/contributing/ai-policy/) | Yes | No | No | Yes |
[Unison](https://github.com/bcpierce00/unison) | [LLM usage](https://github.com/bcpierce00/unison/blob/master/CONTRIBUTING.md#llm-usage) | No | - | - | - | - |
[University of Alaska Anchorage](https://github.com/uaanchorage) | [GSoC/Acceptable-and-Ethical-AI-Use-Policy.md](https://github.com/uaanchorage/GSoC/blob/main/Acceptable-and-Ethical-AI-Use-Policy.md) | Yes* | No | No | Yes | "No vibe code"
[uv](https://github.com/astral-sh/uv) | [AI Policy](https://github.com/astral-sh/.github/blob/main/AI_POLICY.md) | Yes | No | No | Yes |
[Vim Classic](https://vim-classic.org/) | [Free of generative AI](https://sr.ht/~sircmpwn/vim-classic/) | No | - | - | - | - |
[Wagtail](https://wagtail.org/) | [Use of generative AI](https://docs.wagtail.org/en/latest/contributing/general_guidelines.html#general-coding-guidelines) | Yes | Yes | No | Yes |
[Wikipedia](https://wikipedia.org) | [Artificial Intelligence](https://en.wikipedia.org/wiki/Wikipedia:Artificial_intelligence) | No* | - | - | - | Allows a few, very specific uses such as translation assistance.
[WP1](https://wp1.openzim.org/) | [Usage of LLMs/AI coding assistants](https://github.com/openzim/wp1/blob/main/CONTRIBUTING.md#usage-of-llmsai-coding-assistants) | Yes | No | No | Yes |
[Xarray](https://github.com/pydata/xarray) | [AI Usage Policy](https://github.com/pydata/xarray/blob/main/doc/contribute/ai-policy.md) | Yes | No | No | Yes | [Xarray's CLAUDE.md file](https://github.com/pydata/xarray/blob/main/CLAUDE.md) |
[Zig](https://ziglang.org) | [Strict No LLM / No AI Policy](https://ziglang.org/code-of-conduct/#strict-no-llm-no-ai-policy) | No | - | - | - | [Contributor Poker and Zig's AI Ban - rationale for ban](https://kristoff.it/blog/contributor-poker-and-ai/)
[Zulip](https://zulip.com/) | [AI use policy and guidelines](https://github.com/zulip/zulip/blob/main/CONTRIBUTING.md#ai-use-policy-and-guidelines) | Yes | No | Yes | Yes |

## Ongoing discussions

- [Agda](https://wiki.portal.chalmers.se/agda/pmwiki.php): [Blanket ban on LLM-generated contributions#8456](https://github.com/agda/agda/pull/8456)
- [Blender](https://www.blender.org/): [AI Contibutions Policy](https://devtalk.blender.org/t/ai-contributions-policy/44202)
- [Fedora Council Policy Proposal: Policy on AI-Assisted Contributions](https://communityblog.fedoraproject.org/council-policy-proposal-policy-on-ai-assisted-contributions/)
- [FreeBSD](https://www.freebsd.org/): [Policy on generative AI created code and documentation](https://www.freebsd.org/status/report-2025-04-2025-06/core/)
- [GCC](https://gcc.gnu.org/): [Working Group for GCC AI Policy](https://gcc.gnu.org/wiki/working-group-ai-policy)
- [Inkscape - Policy Discussion: Generative AI](https://gitlab.com/inkscape/inkscape-board/-/work_items/5)
- [Jupyter](https://jupyter.org/): [AI-assisted code policy: "Literature Review"](https://github.com/jupyter/governance/issues/326)
- [musl-libc](https://musl.libc.org/): [Tentative policy](https://www.openwall.com/lists/musl/2024/10/19/3)
- [NixOS/nixpkgs](https://github.com/NixOS/nixpkgs): [How do we deal with AI-generated issues? #410741](https://github.com/NixOS/nixpkgs/issues/410741)
- [Rust](https://rust-lang.org): [Policy proposal: No low-effort contributions](https://github.com/rust-lang/leadership-council/issues/273)

## Other references

- [Linux Foundation's Guidance Regarding Use of Generative AI Tools for Open Source Software Development](https://www.linuxfoundation.org/legal/generative-ai)
- [Preparing JOSS for a generative AI future: From code to human creativity and design](https://blog.joss.theoj.org/2026/01/preparing-joss-for-a-generative-ai-future)
- [Navigating LLMs in Open Source: pyOpenSci's New Peer Review Policy](https://www.pyopensci.org/blog/generative-ai-peer-review-policy.html)
- [scikit-learn's AGENTS.md file](https://github.com/scikit-learn/scikit-learn/blob/main/AGENTS.md)
- [agentic-oss-policy: Policy templates for protecting open source projects from autonomous AI agent abuse](https://github.com/guenp/agentic-oss-policy)
- [llama.cpp AGENTS.md file](https://github.com/ggml-org/llama.cpp/blob/master/AGENTS.md#instructions-for-llamacpp)
- [Pi (AI agent toolkit) – AGENTS.md file](https://github.com/badlogic/pi-mono/blob/4ba3e5be229a570187d8efbef5c14c0d5ce40dcc/AGENTS.md)
- [The "Vouch" system for managing trust in contributions](https://github.com/mitchellh/vouch)
- [Good Egg: Trust scoring for GitHub PR authors](https://github.com/2ndSetAI/good-egg)
- [Processing AGENTS.md file](https://github.com/processing/processing4/blob/main/AGENTS.md)
- [p5.js AGENTS.md file](https://github.com/processing/p5.js/blob/main/AGENTS.md)
- [Position Statement on Generative AI in the RSE Workplace](https://github.com/Academic-Data-Science-Alliance/rse-ai-position-statement/blob/main/RSE-AI-Final_Statement.md)
- [Exploring Solutions to Tackle Low-Quality Contributions on GitHub](https://github.com/orgs/community/discussions/185387)
- [LibreHealth](https://gitlab.com/librehealth) GSoC participation policy: [README: The use of AI is forbidden at any point during the program](https://forums.librehealth.io/t/readme-the-use-of-ai-is-forbidden-at-any-point-during-the-program/5400)
- [Superpowers CLAUDE.md file](https://github.com/obra/superpowers/blob/main/CLAUDE.md)
- [rOpenSci's policy on the use of AI on software peer review](https://ropensci.org/blog/2026/02/26/ropensci-ai-policy/)
- [Linux Foundation Report: Open Source and the Future of AI](https://www.linuxfoundation.org/research/ai-exec-forum-2026)
- [Responsible AI Guide](https://responsibleai.guide/)
- [Let's talk about AI slop](https://archestra.ai/blog/only-responsible-ai)
- [Scientific Python](https://scientific-python.org): [Blog post: Community Considerations Around AI Contributions](https://blog.scientific-python.org/scientific-python/community-considerations-around-ai/)

## Acknowledgements

Many thanks to multiple contributors who shared links and contributed in private, on [Mastodon](https://pynews.com.br/@melissawm/116097821572556756) or LinkedIn (let me know if you want attribution :smile:)

## Talks

- [Open source vs. IA: Um panorama das políticas de engajamento atuais](./noss-2026/dist/)
