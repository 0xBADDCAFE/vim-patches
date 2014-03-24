vim-patches
===========

patches applied my Vim.

patch authors
-------------

`*1` kaoriya's patch

  https://bitbucket.org/koron/vim-kaoriya-patches/src

`*2` k-takata's patch

  https://bitbucket.org/k_takata/vim-ktakata-mq/src

reject
------

  I can't apply or original of fixed patches or unsure future.

patch files
-----------

```
VIM\PATCHES
│  0000-kaoriya_marks.diff                    *1
│  0001-rich_icon.diff                        *1
│  0100-embed_manifest.diff                   *1
│  0101-po_install_all.diff                   *1
│  2001-improve_modelines.diff                *1
│  2002-windows_transparency.diff             *1
│  2003-charspace.diff                        *1
│  2004_and_remove-client-edge.diff           *1 *2
│  2005-ambiwidth_auto.diff                   *1
│  2006-init_winsock.diff                     *1
│  2008-sentence_until_punctuation.diff       *1
│  2010-imaf_imsf_on_cui.diff                 *1
│  2520-migemo_feature_7.4.205.diff           *1
│  2530-guess_encode_feature.diff             *1
│  4001-ftp_autolink_2html.diff               *1
│  4002-japanese_punctuation_javadoc.diff     *1
│  build_for_XP_on_msvc2013.diff
│  fastcomplpop.diff                # https://github.com/vim-jp/issues/issues/401
│  improve_dos_test.diff                      *1
│  support-alt-gettext-dll.diff               *2
│  vim-7.4.178-breakindent.diff               *2
│  X001-direct_write-r3.diff                  *1
│  X010fix-autoload_cache.diff                *1
│  
└─reject
        0001-rich_icon.diff                   *1
        2000-efficient_printing.diff          *1
        2004-caption_switch.diff              *1
        2007-refactor_vim_strchr.diff         *1
        2510-uimfep_support.diff              *1
        2520-migemo_feature.diff              *1
        disable_regexp_logs.diff              *1
        remove-client-edge.diff               *2
        tab-xyz.diff                          *2
        X003-csearch_highlight.diff           *1
        X004-eval_rmdir.diff                  *1
        X004_01-rmdir_support_symlinks.diff   *1
        X005-eval_marks.diff                  *1
        X006-enc_considered_setenv.diff       *1
        X007-make_compact_func.diff           *1
        X008-async_job.diff                   *1
        X009-lasteol_impl.diff                *1
        X010-autoload_cache.diff              *1
```
