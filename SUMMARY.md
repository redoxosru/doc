# Операционная система Redox

- [Обзор](overview/welcome.md)
    - [Redox — что это?](overview/what_redox_is.md)
    - [Структура](overview/the_structure.md)
    - [Сторонние проекты](overview/side_projects.md)
    - [Разработчики](overview/developers.md)

- [Введение]()
    - [Redox — что это?](introduction/what_is_redox.md)
    - [Почему Redox?](introduction/why_redox.md)
    - [Почему Rust?](introduction/why_rust.md)
        - [Heartbleed: A case study]()
        - [Unsafes](introduction/unsafes.md)
    - [Почему MIT?](introduction/why_mit.md)
    - [How Redox compares to other operating systems](introduction/how_redox_compares_to_other_operating_systems.md)
    - [The target of Redox]()
    - [Должен ли Redox заменить Linux?](introduction/will_redox_replace_linux.md)

- [Getting started]()
  - [Preparing Redox](./getting_started/preparing_the_build.md)
  - [Compiling Redox](./getting_started/compiling_redox.md)
  - [Exploring Redox](./getting_started/exploring_redox.md)
  - [Questions and feedback](./getting_started/asking_questions_giving_feedback.md)

    -------------------------------------------------------------------------------
- [The design](./design/design.md)
    - [URLs, schemes and resources](./design/urls_schemes_resources.md)
        - [URLs](./design/url/urls.md)
            - [Aren't they weakly typed?]()
            - [Aren't they confusing?]()
            - [How it works under the hood](./design/url/how_it_works.md)
        - [Schemes](./design/scheme/schemes.md)
            - [The root scheme](./design/scheme/the_root_scheme.md)
            - [Writing your own scheme](./design/scheme/writing_a_scheme.md)
            - [Using schemes efficiently]()
        - [Resources](./design/resource/resources.md)
            - [Socket-like](./design/resource/socket_like.md)
            - [File-like](./design/resource/file_like..md)
        - [Stitching it all together](./design/url_scheme_resource/stiching_it_all_together.md)
            - ["Everything is a URL"](./design/url_scheme_resource/everything_is_a_url.md)
            - [An example](./design/url_scheme_resource/example.md)
    - [The kernel](./design/kernel/kernel.md)
        - [Microkernels](./design/kernel/microkernels.md)
            - [Advantages of microkernels](./design/kernel/advantages.md)
            - [Disadvantages of microkernels](./design/kernel/disadvantages.md)
            - [Performance of microkernels]()
        - [Syscalls]()
            - [Linux compatibility]()
        - [Scheduling]()
        - [Memory management]()
        - [Drivers]()
