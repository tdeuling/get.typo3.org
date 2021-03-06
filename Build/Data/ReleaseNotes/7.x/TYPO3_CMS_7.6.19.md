Release Notes for TYPO3 CMS 7.6.19
==================================

This document contains information about TYPO3 CMS 7.6.19 which was
released on June 20th, 2017.

News
----

This version is a maintenance release and contains bug fixes only.

Download
--------

<https://typo3.org/download/>

MD5 checksums
-------------

    cddd4d333c7899bc0bd452c75687b5ec  typo3_src-7.6.19.tar.gz
    55d1fbcfcb81845517015d64ae869c88  typo3_src-7.6.19.zip

SHA256 checksums
----------------

    4496c606e179a996636a33fbc681bd649fcd1021ea60fcb295dbdfee9750483f  typo3_src-7.6.19.tar.gz
    cc23bb2334d16432ffa08623253ccfebda4808dda1e7c03d33b3ac8082cba821  typo3_src-7.6.19.zip

Upgrading
---------

The [usual upgrading
procedure](https://docs.typo3.org/typo3cms/InstallationGuide/) applies.
No database updates are necessary.\
It might be required to clear all caches; the “important actions”
section in the TYPO3 Install Tool offers the accordant possibility to do
so.

Changes
-------

Here is a list of what was fixed since
[7.6.18](TYPO3_CMS_7.6.18 "wikilink"):

    7e72aa52ef [RELEASE] Release of TYPO3 7.6.19
    c35c325539 [BUGFIX] Prevent uncaught exception in Import/Export controller
    b4af653c73 [BUGFIX] Select suitable distribution version in em
    1d98daf126 [BUGFIX] Remove possibly undefined constant from test bootstraps
    e8f97da179 [BUGFIX] Remove manually set database row
    20a9592cac [BUGFIX] Prefix single digit dates with 0 instead of whitespace
    5df7e2c919 [BUGFIX] Wrong computed baseURL with FE editing RTE
    88fd7dfb3f [BUGFIX] Return http_code for HEAD requests in GeneralUtility::getUrl
    18dec8f9ec [BUGFIX] Detect upper limit of database server version
    3f5726639b [BUGFIX] FormEngine: Show correct error message (render)Type is unknown
    665557e231 [TASK] Add sitemap to sysext:core/Documentation
    59b68d4ef2 [BUGFIX] Hide empty descriptions in textmedia in page module
    3c451b4708 [BUGFIX] Avoid unnecessarily fetching file for processing
    473a18361a [BUGFIX] Ensure correct URL generation with http_build_query()
    e2c8ffe9da [BUGFIX] DBAL: Assure all optional query array parameters are set
    389e79c30b [BUGFIX] Use EXEC_TIME for sys_log entry instead of time()
    32f18c8792 [BUGFIX] HtmlArea: Use getAttribute() directly
    c150986e95 [TASK] Unit test fails with recent PHP releases
    4dc552d407 [BUGFIX] Unset current file in generic Content Object Renderer
    33bce7def4 [BUGFIX] Add UI blocker to prevent loading issues in FormEngine
    96a266ad6b [TASK] Throw explicit exception on missing link handler class
    54e2b69989 [BUGFIX] DBAL: Ensure correct mysqli resource for admin_get_tables query
    63a3a08c3d [BUGFIX] Use renderType selectSingle for field t3_tables of sys_action
    4c6ba8aa2f [BUGFIX] Reload page tree after deleting pages
    dbc5b07200 [BUGFIX] INCLUDE_TYPOSCRIPT condition use correct ConditionMatcher
    5ac23cf344 [BUGFIX] Add missing SQL index for EM repository update
    2648d87198 [BUGFIX] Load PageTSconfig in localconf for LinkHandler
    bee2c439ac [BUGFIX] Add `config.contentObjectExceptionHandler` to tsref.xml
    1685e6e95e [TASK] Show copy and cut buttons in filelist options
    ce160ba5b1 [BUGFIX] Do not prefix FAL file links with absRefPrefix
    2f82503a34 [TASK] Move CSV fixtures handling to FunctionalTestCase
    4aee4375a3 [BUGFIX] Do not ask for current password if admin
    535958b8b4 [BUGFIX] Use real BE user for logging user setting changes
    505d1dcfb6 [TASK] Set TYPO3 version to 7.6.19-dev


