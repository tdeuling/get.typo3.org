Release Notes for TYPO3 CMS 6.1.6
=================================

This document contains information about TYPO3 CMS 6.1.6 which was
released on November 26th, 2013.

News
----

This release is a bug fix release.

Notes
-----

This is part of a combined release of TYPO3 CMS 4.5.31, 4.7.16, 6.0.11
and 6.1.6.

Download
--------

<https://typo3.org/download/>

MD5 checksums
-------------

    2bbc680e04c6e49f0c2914fda6a96cee  blankpackage-6.1.6.tar.gz
    f09ae60cc2f0b1f5ab29c14f1b8c385e  blankpackage-6.1.6.zip
    eb17f390579bb4b465e80888686a1e03  dummy-6.1.6.tar.gz
    5db7f9081afe4ad199223cbd9543a29e  dummy-6.1.6.zip
    a14d3ce72bcb08f5f3cdc2a9db9e763f  governmentpackage-6.1.6.tar.gz
    526c5d13e3b084cfd2daa26e4e1ab367  governmentpackage-6.1.6.zip
    f43998da2c2940c9f197f8f36c43fbbf  introductionpackage-6.1.6.tar.gz
    fcc96975b907a6f27c0113a985cc634a  introductionpackage-6.1.6.zip
    69cae380b6de1ad584248ac3d202e44f  typo3_src+dummy-6.1.6.zip
    a8dba1a604709777d86674d719e1345f  typo3_src-6.1.6.tar.gz
    785c48ae26f2752306dd4711c5b5081e  typo3_src-6.1.6.zip

Upgrading
---------

The [usual upgrading
procedure](https://docs.typo3.org/typo3cms/InstallationGuide/) applies.
No database updates are necessary.

Changes
-------

Here is a list of what was fixed since [6.1.5](TYPO3_6.1.5 "wikilink"):

    2013-11-26  3f69433                  [RELEASE] Release of TYPO3 6.1.6 (TYPO3 Release Team)
    2013-11-26  3eda399  #53918          [BUGFIX] t3skin calls addIconSprite for each lang (Michiel Roos)
    2013-11-24  93ed8d2  #51650          [BUGFIX] TS: Allow "0" as strPad.padWith (Lars Peipmann)
    2013-11-24  aed6051  #15958          [BUGFIX] Reload list module on clickmenu action (Bernhard Kraft)
    2013-11-21  7042298  #53802          [BUGFIX] Fix moving/copying files and folders between storages (Frans Saris)
    2013-11-21  b78c694  #53844          [BUGFIX] Fix regression in ResourceCompressor (Markus Klein)
    2013-11-20  3d3de05  #53243          [BUGFIX] Filemtime / Filesize trigger warning (Tomita Militaru)
    2013-11-20  6c5d53d  #53458          [BUGFIX] Fluid paginate widget wrong number of links (Klaas Johan Kooistra)
    2013-11-20  52b751e                  Revert "[BUGFIX] Page module: Allow to paste in empty columns" (Markus Klein)
    2013-11-20  dbcaf93  #44002,#35980,  [BUGFIX] Page module: Allow to paste in empty columns (Bernhard Kraft)
    2013-11-19  023014c  #38766          [BUGFIX] l10n_mode for "pages" table and group fields. (Johannes Feustel)
    2013-11-19  9d97a70  #53773          [BUGFIX] Fix JS error in lang module (Markus Klein)
    2013-11-19  170f084  #53750          [BUGFIX] Scheduler extension sql file is invalid (Michiel Roos)
    2013-11-19  abcd5e9  #34544          [BUGFIX] fix javascript error "TBE_EDITOR not defined" in sys_action (Ralf Hettinger)
    2013-11-19  ba82fac  #51998          [BUGFIX] ExtDirect StateProvider should store all settings (Johannes Feustel)
    2013-11-19  571c8c9  #53746          [TASK] Optimization in AbstractViewHelper (Wouter Wolters)
    2013-11-18  33b0d1b  #53707          [BUGFIX] Rename hook in VariableFrontend.php (Nicole Cordes)
    2013-11-18  fbd9379  #53711          [BUGFIX] additionalAttributes for be.buttons.icon-VH misses hsc (Markus Klein)
    2013-11-18  fa87ad9  #53014          [BUGFIX] Check for query failures in admin methods (Thomas Maroschik)
    2013-11-15  7223b78                  Revert "[BUGFIX] EM: Fetch list as html, not as json" (Helmut Hummel)
    2013-11-14  62f7e87  #45724          [BUGFIX] FILES.folder does not work (Stefan Froemken)
    2013-11-14  c65640d  #51234          [BUGFIX] Move beuser property mappings to global scope (Philipp Gampe)
    2013-11-14  35a95b0  #17493          [BUGFIX] Fix broken edit icons on cType HTML (Stefan Neufeind)
    2013-11-13  fd66dfc  #25157,#45550   [BUGFIX] Distinguish unassigend columns and colPos 0 (Georg Ringer)
    2013-11-13  0641f4f  #51918          [BUGFIX] Native date and datetime values do not consider timezone (Oliver Hader)
    2013-11-12  9aa1fa2  #52926          [BUGFIX] Compressor resolves dots in filenames correctly (Christian Kuhn)
    2013-11-12  fa77640  #53115          [BUGFIX] T3editor: Make errors/exceptions show correctly (Stefan Neufeind)
    2013-11-12  259c64d  #22136          [BUGFIX] Fix menu popup for all IE versions (Alexander Opitz)
    2013-11-12  ffd8480  #52934          [BUGFIX] dataTables: Avoid sending cookie-data too often (Stefan Neufeind)
    2013-11-12  c3b0ebc  #53399          [BUGFIX] Wrong usage-text for cli_dispatch (Tomita Militaru)
    2013-11-12  dcdb7bb  #52904          [BUGFIX] Evaluator in JS fails with namespaces (Stefan Aebischer)
    2013-11-12  cf50919  #53538          [BUGFIX] Make be.buttons.icon-ViewHelper extensible (Stefan Neufeind)
    2013-11-11  fbb19b4  #52727          [TASK] Hard-coded labels in file collections (Tomita Militaru)
    2013-11-11  3dd29c3  #37948          [BUGFIX] Correctly append additionalTreelistUpdateFields (Bart Dubelaar)
    2013-11-11  a3153a3  #52488          [BUGFIX] Call to FlashMessageQueue::addMessage() method in extbase (Markus Klein)
    2013-11-11  b61f34f  #53423          [BUGFIX] EM: Fetch list as html, not as json (Stefan Neufeind)
    2013-11-10  093d7ac  #52173          [BUGFIX] Correct storage selection (follow-up) (Ernesto Baschny)
    2013-11-09  7015242  #53477          [TASK] Fix superfluous strlen() on constant strings (Steffen Ritter)
    2013-11-09  827bf21  #47040          [BUGFIX] Enable treeConfig overriding by Page TSconfig (Stefan Froemken)
    2013-11-09  0b03e72  #53195          [BUGFIX] T3editor: Honour fileDenyPattern on saving included TS (Stefan Neufeind)
    2013-11-08  6f1625f  #29179          [BUGFIX] Escape title, extension, description of scheduler tasks (Tomita Militaru)
    2013-10-23  d34bde3  #31572          [BUGFIX] Exception using cObject FORM in TypoScript (Andreas Bouche)
    2013-10-18  840a3a6  #35073          [BUGFIX] Enable BE search for multiple mountpoints (Georg Ringer)
    2013-10-17  775a077  #52931          [TASK] Exclude central Modernizr from concatenation (Stefan Neufeind)
    2013-10-17  0382419  #52570          [TASK] Tests for Persistence\Generic\Backend::getIdentifierByObject (Stefan Neufeind)
    2013-10-17  b78dc4e  #50548          [BUGFIX] Getting the identifier for a lazy object fails (Marc Bastian Heinrichs)
    2013-10-16  2f1fb3f  #52529          [BUGFIX] Suppress empty tag names in output of array2xml (Markus Hoelzle)
    2013-10-16  b218036  #52823          [BUGFIX] Preserve vendor name in refering request (Thomas Maroschik)
    2013-10-16  88cc508                  [BUGFIX] Follow-Up: Fatal error due to missing use statement (Sascha Egerer)
    2013-10-15  1761850  #52845          [BUGFIX] Moving folders fails (Oliver Hader)
    2013-10-15  be9b7c7  #50802          [BUGFIX] Only load folder contents if folder is initialised (Frans Saris)
    2013-10-15  ce693d8  #52824          [BUGFIX] Superfluous usage of ObjectManagerException (Oliver Hader)
    2013-10-15  8be996a  #51707          [FEATURE] Add getValidators to AbstractCompositeValidator (Stefan Froemken)
    2013-10-15  992e4ef  #52771          [BUGFIX] Use callback in preg_replace in RemoveXSS (Jigal van Hemert)
    2013-10-14  50942c2  #52773          [BUGFIX] Detect unix-styled absolute paths on Windows systems (Nicole Cordes)
    2013-10-13  2889f13  #52759          [BUGFIX] Object passed to date() (Xavier Perseguers)
    2013-10-12  f4f2756  #52731          [TASK] Use 6.1 branch in travis-integration for travis (Christian Kuhn)
    2013-10-12  d68c114  #52728          [BUGFIX] Use BackendUtility use statement (Anja Leichsenring)
    2013-10-12  33d4415  #52104          [BUGFIX] Wrong calculation of maximum value for checkbox fields (Nicole Cordes)
    2013-10-12  e3d02ef  #52715          [BUGFIX] Prevent empty newline below scheduler-task-name (Stefan Neufeind)
    2013-10-11  a3f8dfe  #52708          [BUGFIX] DataMapFactory::resolveTableName must remove leading backslashes (Alexander Schnitzler)
    2013-10-11  9b4462b  #50912          [BUGFIX] BackendUtility::viewOnClick() called with non-integer (Oliver Hader)
    2013-10-11  d910b2b  #51051          [BUGFIX] Clear_cache() must not consider page ids lower than 0 (Oliver Hader)
    2013-10-11  1483967  #37611          [BUGFIX] Select available page when changing WS (Thorsten Kahler)
    2013-10-11  f4e1b0e  #52636          [BUGFIX] Copy records to target page before origin page is deleted (Timo Webler)
    2013-10-11  ed4e368  #17551          [BUGFIX] Create workspace placeholder with processed field content (Sascha Egerer)
    2013-10-11  6f47aa5  #36573          [BUGFIX] Add workspace overlay for fetched records. (Timo Webler)
    2013-10-11  d6b57e8  #37209          [BUGFIX] WS preview shows pages changes from all WS (Thorsten Kahler)
    2013-10-11  fcad15e  #52530          [BUGFIX] Delete modified record in WS just deletes WS version (Sascha Egerer)
    2013-10-11  3ac3429  #37065          [BUGFIX] Don't show duplicates in workspace preview (Timo Webler)
    2013-10-10  394d12e  #52178          [BUGFIX] Cannot upload an extension as zip (Xavier Perseguers)
    2013-10-07  8f1afaf  #49538          [BUGFIX] Fields of type file_reference are not properly indexed (Martin Borer)
    2013-10-07  98625ae  #52546          [BUGFIX] Missing closing tag in ElementBrowser (Philipp Gampe)
    2013-10-05  dc5b2f1  #52469          [TASK] Use instanceof comparison instead of string comparison (Benjamin Serfhos)
    2013-09-30  6b2512a  #43540          [BUGFIX] TS is fetched from cache incorrectly sometimes (Dmitry Dulepov)
    2013-09-28  3a3edf1  #48809,#51730,  [BUGFIX] Fix wrong handling of php and TYPO3 dependencies (Susanne Moog)
    2013-09-28  9535891  #51329          [BUGFIX] Initialize extension name in command requests (Alexander Stehlik)
    2013-09-27  06723a0  #52045          [BUGFIX] EmConfUtility accesses non-arrays (Markus Klein)
    2013-09-27  219c381  #51588          [BUGFIX] Clear cached menu by tag (Zbigniew Jacko)
    2013-09-27  b41847a  #50437          [BUGFIX] Fix jumpToUrl()-Usage in Element Browser (Benjamin Pick)
    2013-09-26  6bdc8ad  #52091,#51684   [BUGFIX] Check for string before using strlen (Kilian Hann)
    2013-09-26  9be6739  #52266          [BUGFIX] groupFor-VH does not work with @lazy (Stefan Froemken)
    2013-09-26  d3bf620  #50913          [BUGFIX] Fix PHP warning trigged in getAuthInfoArray() (Christian Finkemeier)
    2013-09-26  993dd5d  #52316          [BUGFIX] Fatal in DefaultConfiguration (Christian Kuhn)
    2013-09-26  bb94fe0  #52305          [BUGFIX] Configure main extbase caches for unlimited entry lifetime (Christian Kuhn)
    2013-09-26  52ff400  #52295          [TASK] Use SimpleFileBackend for t3lib_l10n cache (Christian Kuhn)
    2013-09-25  f0fe1c4  #52226          [BUGFIX] EM does not link to docs.typo3.org (Xavier Perseguers)
    2013-09-25  db5fb24  #51116          [BUGFIX] Increase performance of exports for caches (Markus Klein)
    2013-09-25  28ee210  #52243          [BUGFIX] Remove duplicate exception code (Fabien Udriot)
    2013-09-24  3f53e6b  #52173          [BUGFIX] Correct storage selection (common prefixes) (Ernesto Baschny)
    2013-09-24  1d17a21  #52201          [BUGFIX] Fix broken Unit-test for #44825 (Wouter Wolters)
    2013-09-23  ae9b606  #44825          [BUGFIX] Fix page.headerData + USER_INT (Helmut Hummel)
    2013-09-20  7d08d29  #48912          [BUGFIX] Increase length of identifier field in sys_file (Nicole Cordes)
    2013-09-20  e0600ed  #52056          [BUGFIX] Wrong exception on renaming folder (Francois Suter)
    2013-09-19  9423c2c  #49328          [BUGFIX] Fix PHP warning when writing to Backend user log (Alexander Stehlik)
    2013-09-17  fd534b6  #45859          [BUGFIX] Faulty expand/collapse behavior in Element Browser (Oliver Hader)
    2013-09-17  ce68bcd  #19045          [BUGFIX] Fix cropping of transparent gifs with im6. (Stefan Neufeind)
    2013-09-17  fb5bbbf  #50907          [BUGFIX] Form Wizard: Adds mouse pointer to docheader icons (Ernesto Baschny)
    2013-09-13  0fe373b  #51981          [BUGFIX] Also consider JPEG files for IM/GM (Markus Klein)
    2013-09-12  b0c54dc  #51803          [TASK] Use a 401 header if login is not successful (Georg Ringer)
    2013-09-12  7169032  #47744          [BUGFIX] Replace SHOW DATABASE by query to schema (Alexander Opitz)
    2013-09-12  ddf74b0  #51891          [BUGFIX] Call to undefined method setTemplateFile (Wouter Wolters)
    2013-09-12  66ad5e7                  [TASK] Set TYPO3 version to 6.1.6-dev (TYPO3 Release Team)


