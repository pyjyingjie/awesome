>![](http://www.easyicon.net/api/resize_png_new.php?id=1174989&size=16)[emacs-tw/awesome-emacs](https://github.com/emacs-tw/awesome-emacs)

* Awesome Emacs

A community driven list of useful Emacs packages, libraries and others.

Most of the following packages are available in [[https://github.com/milkypostman/melpa][MELPA]]. We recommend installing packages via it.

#+BEGIN_QUOTE
*Table of Contents*
- [[#awesome-emacs][Awesome Emacs]]
  - [[#interface-enhancement][Interface Enhancement]]
  - [[#file-manager][File Manager]]
  - [[#navigation][Navigation]]
  - [[#project-management][Project management]]
  - [[#programming][Programming]]
    - [[#completion][Completion]]
    - [[#code-folding][Code Folding]]
    - [[#error-checking][Error Checking]]
  - [[#programming-language][Programming Language]]
    - [[#python][Python]]
    - [[#lisp-family][Lisp Family]]
      - [[#common-lisp][Common Lisp]]
      - [[#scheme][Scheme]]
      - [[#clojure][Clojure]]
    - [[#web--javascript--css][Web / JavaScript / CSS]]
    - [[#sml][SML]]
    - [[#ocaml][OCaml]]
    - [[#erlang][Erlang]]
    - [[#haskell][Haskell]]
  - [[#visual][Visual]]
    - [[#keys-cheat-sheet][Keys Cheat Sheet]]
  - [[#editing][Editing]]
    - [[#kill-ring][Kill-ring]]
  - [[#note][Note]]
  - [[#version-control][Version control]]
  - [[#integration][Integration]]
    - [[#console][Console]]
    - [[#search][Search]]
      - [[#ack][Ack]]
      - [[#ag][Ag]]
      - [[#pt][Pt]]
    - [[#pastebin][Pastebin]]
    - [[#google][Google]]
  - [[#latex][LaTeX]]
  - [[#internet][Internet]]
    - [[#mail][Mail]]
    - [[#irc][IRC]]
    - [[#social-network][Social Network]]
    - [[#rss][RSS]]
  - [[#package-manager][Package Manager]]
  - [[#library][Library]]
  - [[#appearance][Appearance]]
  - [[#theme][Theme]]
  - [[#fun][Fun]]
  - [[#starter-kit][Starter Kit]]
- [[#contributing][Contributing]]
  - [[#generate-table-of-contents][Generate "Table of Contents"]]
  - [[#emacs-built-in-packages][Emacs Built-In Packages]]
#+END_QUOTE

** Interface Enhancement

   - [[http://www.emacswiki.org/emacs/InteractivelyDoThings][IDO]] - =[built-in]= Interactively do things with buffers and files.
   - [[https://github.com/emacs-helm/helm][Helm]] - A powerful completion and selection narrowing framework.
   - [[https://github.com/nonsequitur/smex/][smex]] - A smart M-x enhancement for Emacs.
   - [[https://github.com/dholm/tabbar.git][tabbar]] - Display a tab bar in the header line.
   - [[http://gitorious.org/evil/pages/Home][Evil]] - An *e* xtensible *vi* *l* ayer: manipulate Emacs with Vi key binding.
   - [[https://github.com/zk-phi/sublimity][sublimity]] - smooth-scrolling, minimap inspired by the sublime editor.
   - [[http://www.emacswiki.org/emacs/WinnerMode][winner]] - =[built-in]= "Undo"(and "redo") changes in the window configuration with the key commands.
   - [[https://github.com/knu/elscreen][ElScreen]] - Utility for multiple screens.

** File Manager

   - [[http://www.emacswiki.org/emacs/DiredMode][Dired]] - =[built-in]= *Dir* ectory *Ed* itor. A customizable great file manager.
   - [[http://www.emacswiki.org/emacs/DiredPlus][Dired+]] - Functional & interface extensions for dired.
   - [[http://www.emacswiki.org/emacs/NeoTree][NeoTree]] - A emacs tree plugin like NERD tree for Vim.
   - [[http://www.emacswiki.org/emacs/SrSpeedbar][Sr Speedbar]] - Same frame speedbar.
   - [[https://github.com/m2ym/direx-el][Direx]] - directory tree explorer

** Navigation

   - [[http://www.emacswiki.org/emacs/WindMove][windmove]] - =[built-in]= Tired with =C-x o=? Now you can use =shift+arrows= to jump between windows.
   - [[https://github.com/winterTTr/ace-jump-mode][Ace jump]] - A quick cursor jump mode.
   - [[https://raw.github.com/emacsmirror/emacswiki.org/master/goto-last-change.el][goto-last-change]] - Move point through buffer-undo-list positions.
   - [[https://github.com/ShingoFukuyama/helm-swoop][Helm-swoop]] - Efficiently jump between matched string/lines.
   - [[https://github.com/syohex/emacs-anzu][anzu]] - displays current match and total matches.
   - [[http://www.emacswiki.org/emacs/ImenuMode][imenu]] - =[built-in]= Menus for accessing locations in documents.
   - [[https://github.com/vitoshka/imenu-anywhere][imenu-anywhere]] - IDO/Helm imenu tag selection across all buffers with the same mode.
   - [[https://github.com/dustinlacewell/emacs-minimap][Minimap]] - A SublimeText-style minimap sidebar.

** Project management

   - [[https://github.com/bbatsov/projectile][Projectile]] - Project Interaction Library for Emacs.
   - [[https://github.com/rejeep/prodigy.el][Prodigy]] - Manage external services from within Emacs.
   - [[https://github.com/d11wtq/fiplr][Fiplr]] - An Emacs Fuzzy Find in Project Package.
   - [[https://github.com/sabof/project-explorer][Project-Explorer]] - a tree project explorer (integrates with projectile)

** Programming

   - [[http://cedet.sourceforge.net/][CEDET]] - =[built-in]= an advanced development environment in Emacs.
   - [[http://www.xref.sk/xrefactory/emacs.html][Xrefactory]] - A refactoring browser for Emacs.
   - [[https://github.com/capitaomorte/yasnippet][YASnippets]] - Template system.
   - [[https://github.com/areina/helm-dash][Helm-dash]] - Browse [[http://kapeli.com/dash][Dash]] docsets via Helm interface.
   - [[https://github.com/redguardtoo/evil-nerd-commenter][evil-nerd-commenter]] - Comment/uncomment lines efficiently. Like Nerd Commenter in Vim.  This program can be used independently without evil-mode.
   - [[https://github.com/Fuco1/smartparens][SmartParens]] - Deals with parens pairs and tries to be smart about it
   - [[https://github.com/zk-phi/indent-guide][indent-guide]] - Show vertical lines to guide indentation

*** Completion

    - [[https://github.com/auto-complete/auto-complete][Auto-Completion]] - An intelligent auto-completion extension with great interface.
    - [[http://company-mode.github.io/][Company]] - A text completion framework.
    - [[https://github.com/lewang/flx][flx]] - Fuzzy matching for Emacs à la Sublime Text.
    - [[http://www.emacswiki.org/emacs/AbbrevMode][abbrev]] - =[built-in]= Abbreviation expander

*** Code Folding

    - [[http://www.emacswiki.org/emacs/HideShow][hideshow]] - =[built-in]= Folding regions by balanced-expression code.
      - [[http://www.emacswiki.org/emacs/download/hideshowvis.el][hideshowvis]] - Based on =hideshow=, just display its nodes on fringe.

*** Error Checking

    - [[http://www.emacswiki.org/emacs/FlyMake][FlyMake]] - =[built-in]= on-the-fly syntax checks on files using external tools.
    - [[https://github.com/flycheck/flycheck][Flycheck]] - modern on-the-fly syntax checking meant to be a replacement to =FlyMake=

** Programming Language

*** Python

    - [[https://github.com/tkf/emacs-jedi][Jedi]] - A Python auto-completion package.
    - [[https://github.com/jorgenschaefer/elpy][Elpy]] - An Emacs Python development environment.
    - [[https://github.com/proofit404/anaconda-mode][anaconda-mode]] - Code navigation, documentation lookup and completion for Python.
    - [[https://github.com/porterjamesj/virtualenvwrapper.el][virtualenvwrapper.el]] - Manage virtualenv from inside Emacs.

*** Lisp Family

    - [[http://www.emacswiki.org/emacs/ParEdit][Paredit]] - Minor mode for editing parentheses. Strict parenthesis auto-pairing and easy depth adjustment. Compatible with Lisp/Scheme/Clojure.

**** Common Lisp

     - [[http://common-lisp.net/project/slime/][SLIME]] - A fully-functional IDE for Common Lisp development, with debugger, REPL.

**** Scheme

     - [[http://www.neilvandyke.org/quack/][Quack]] - Enhanced Emacs Support for Editing and Running Scheme Code.
     - [[http://www.nongnu.org/geiser/][Geiser]] - Intergrated development with Guile and Racket.

**** Clojure

     - [[https://github.com/clojure-emacs/clojure-mode][Clojure mode]] - A major mode for clojure.
     - [[https://github.com/clojure-emacs/cider][Cider]] - Clojure IDE and REPL.
     - [[https://github.com/mpenet/clojure-snippets][Clojure snippets]] - Clojure snippets with yasnippet.

*** Web / JavaScript / CSS

    - [[https://github.com/mooz/js2-mode/][js2-mode]] - Improved JavaScript editing mode.
    - [[https://github.com/skeeto/skewer-mode][skewer-mode]] - live interact with JavaScript, CSS, and HTML in a web-browser.
    - [[http://js-comint-el.sourceforge.net/][js-comint.el]] - Run an inferior javascript REPL process in Emacs.
    - [[http://web-mode.org/][web-mode]] - major mode for editing various html templates (PHP, JSP, ASP, ERB...etc).
    - [[https://github.com/smihica/emmet-mode][emmet]] - [[http://emmet.io/][Emmet]] support for Emacs.
    - [[https://github.com/skeeto/impatient-mode][impatient-mode]] - See your changes in the browser as you type.
    - [[https://github.com/ejmr/php-mode][php-mode]] - Major mode for PHP programming.

*** SML

    - [[http://www.iro.umontreal.ca/~monnier/elisp/][SML mode]] - a major Emacs mode for editing Standard ML source code.

*** OCaml

    - [[https://github.com/ocaml/tuareg][tuareg]] - a Caml mode for Emacs.
    - [[http://www.typerex.org/][TypeRex]] - a set of tools for developing in OCaml.

*** Erlang

    - [[http://www.erlang.org/doc/apps/tools/erlang_mode_chapter.html][erlang]] - the official Erlang mode for Emacs.
    - [[https://github.com/massemanet/distel][distel]] - Distel is a library for Emacs<->Erlang communication, plus a suite of tools built on top of it, such as a debugger front-end.
    - [[https://github.com/tjarvstrand/edts][EDTS]] - EDTS is meant to be a able to replace Distel but only provides part of the most commonly used of Distel's features.
    - [[https://github.com/RefactoringTools/Wrangler][Wrangler]] - Wrangler is a mode that supports interactive refactoring of Erlang programs

*** Haskell

    - [[https://github.com/haskell/haskell-mode][haskell-mode]] - major mode for Haskell
    - [[https://github.com/chrisdone/structured-haskell-mode][structured-haskell-mode]] - minor mode for structured editing of Haskell
    - [[https://github.com/alanz/HaRe][HaRe]] - Haskell refactoring tool with emacs integration
    - [[http://www.mew.org/~kazu/proj/ghc-mod/en/][ghc-mod]] - backend to provide e.g. type information with an emacs frontend

** Visual

   - [[http://www.emacswiki.org/emacs/UndoTree][undo-tree]] - Visualize the whole undo history in buffer as a tree, and you can access anywhere in it.
   - [[https://github.com/nschum/highlight-symbol.el][highlight-symbol]] - Auto/manually highlight the same symbols in code, navigate in them, or replace string.
   - [[https://github.com/jlr/rainbow-delimiters][rainbow-delimiters]] - Highlights parentheses, brackets, and braces according to their depth.
   - [[https://julien.danjou.info/projects/emacs-packages][rainbow-mode]] - Display color on color-code string (hex/rgb) directly.
   - [[https://github.com/benma/visual-regexp.el][visual-regexp]] - Replace via RegExp, with real-time visual feedback directly in the buffer.
   - [[https://github.com/benma/visual-regexp-steroids.el/][visual-regexp-steroids]] - The same as visual-regexp, but use modern regular expressions instead of Emacs-style.
   - [[http://www.emacswiki.org/emacs/WhiteSpace][whitespace]] - =[built-in]= Visualize blanks (tab/space/newline).
   - [[https://github.com/coldnew/linum-relative][linum-relative]] - display relative line number in the left margin in emacs.

*** Keys Cheat Sheet

   - [[https://github.com/mickeynp/discover.el][discover.el]] - Discover more of emacs with well-categorized context menus.
   - [[https://github.com/kbkbkbkb1/guide-key][guide-key]] - Displays the available key bindings automatically and dynamically.
   - [[https://github.com/aki2o/guide-key-tip][guide-key-tip]] - Tooltip version of guide-key.

** Editing

   - [[https://github.com/magnars/multiple-cursors.el][Multiple cursors]] - Mark, edit multiple lines at once.
   - [[https://github.com/coldnew/pangu-spacing][pangu-spacing]] - Minor-mode to automatically add space between CJK and Latin characters.
   - [[https://github.com/soutaro/hungry-delete.el][hungry-delete]] - Delete an entire block of whitespace at point.
   - [[https://github.com/rejeep/drag-stuff.el][Drag Stuff]] - Drag Stuff is a minor mode for Emacs that makes it possible to drag stuff (words, region, lines) around in Emacs.
   - [[https://github.com/magnars/expand-region.el][expand-region.el]] - Increase selected region by semantic units.
   - [[https://github.com/magnars/multifiles.el][multifiles.el]] - View and edit parts of multiple files in one buffer.

*** Kill-ring

   - [[https://github.com/waymondo/popup-kill-ring][Popup-killring]] - Browse kill-ring with popup menu.
   - [[https://github.com/browse-kill-ring/browse-kill-ring][Browse-kill-ring]] - Visually navigate kill-ring.

** Note

   - [[http://orgmode.org/][Org]] - =[built-in]= Write notes, GTD, authoring, publish and wash dishes.
   - [[http://mwolson.org/projects/EmacsMuse.html][Emacs Muse]] - a publishing environment for Emacs.

** Version control

   - [[http://magit.github.io/][Magit]] - Interacting with git.
   - [[https://github.com/dgtized/github-clone.el][github-clone.el]] - Fork and clone Github projects from Emacs.
   - [[https://github.com/magit/git-modes][git-rebase-mode]] - Major mode for editing git rebase files
   - [[https://github.com/pidu/git-timemachine][git-timemachine]] - Step through historic versions of git controlled files.
   - [[https://github.com/syohex/emacs-git-gutter][git-gutter]] - Indicator the modified lines via git diff.

** Integration

*** Console

    - [[http://www.emacswiki.org/emacs/CategoryEshell][EShell]] - =[built-in]= A shell-like command interpreter implemented in Emacs Lisp.
    - [[http://www.emacswiki.org/emacs/AnsiTerm][Term]] - =[built-in]= A terminal emulator in Emacs.
    - [[https://github.com/purcell/exec-path-from-shell][exec-path-from-shell]] - Get environment variables such as $PATH from the shell for Mac user.
    - [[http://www.emacswiki.org/emacs/download/multi-term.el][multi-term]] - Managing multiple terminal buffers in Emacs.

*** Search

**** Ack

    - [[https://github.com/jhelwig/ack-and-a-half][ack-and-a-half]] - Yet another emacs front-end to ack.
    - [[http://nschum.de/src/emacs/full-ack/][full-ack]] - An Emacs front-end for ack.
    - [[https://github.com/syohex/emacs-helm-ack][helm-ack]] - Use Ack with Helm interface.

**** Ag

     - [[https://github.com/Wilfred/ag.el][ag.el]] - An Emacs frontend to Ag ("the silver searcher" ack replacment)
     - [[https://github.com/syohex/emacs-helm-ag][helm-ag]] - Ag with helm interface

**** Pt

     - [[https://github.com/bling/pt.el][pt.el]] - An emacs front-end for Pt, the [[https://github.com/monochromegane/the_platinum_searcher][Platinum Searcher]].

*** Pastebin

    - [[https://github.com/defunkt/gist.el][gist.el]] - Paste Gist in Emacs.
    - [[https://github.com/mhayashi1120/yagist.el][yagist.el]] - Yet another Gist integration.
    - [[https://github.com/gregnewman/dpaste.el][dpaste.el]] - Emacs mode to post to dpaste.com.

*** Google

    - [[http://github.com/Bruce-Connor/emacs-google-this][google-this]] - A set of functions and bindings to google under point.
    - [[https://github.com/atykhonov/google-translate][google-translate]] - Interface to Google Translate.
    - [[http://emacspeak.googlecode.com/svn/trunk/lisp/g-client/][g-client]] - Google client for Emacs.

** LaTeX

   - [[http://www.gnu.org/software/auctex/][AUCTeX]] - an extensible package for writing and formatting TeX files.
   - [[http://www.emacswiki.org/emacs/LaTeXPreviewPane][latex-preview-pane]] is a minor mode for Emacs that enables you to preview your LaTeX files directly in Emacs.

** Internet

*** Mail

     - [[http://www.emacswiki.org/emacs/CategoryGnus][Gnus]] - =[built-in]= Reading e-mail and Usenet news.
     - [[http://www.emacswiki.org/emacs/MessageMode][Messages]] - =[built-in]= Composing and sending messages inside Emacs.
     - [[http://www.djcbsoftware.nl/code/mu/mu4e.html][mu4e]] - an e-mail client for emacs
     - [[http://notmuchmail.org/][notmuch]] - A mail indexer which can serve as a complete client with its emacs integration

*** IRC

    - [[http://www.emacswiki.org/emacs/ERC][ERC]] - =[built-in]= A powerful, modular, and extensible IRC client.
    - [[http://www.nongnu.org/riece/index.html.en][Riece]] - an IRC client for Emacs.
    - [[http://www.emacswiki.org/emacs/rcirc][Rcirc]] - =[built-in]= Next generation IRC client.

*** Social Network

    - [[http://twmode.sourceforge.net/][Twittering mode]] - Major mode for Twitter.

*** RSS

    - [[https://github.com/skeeto/elfeed][Elfeed]] - RSS Reader for Emacs.

** Package Manager

   - [[http://www.emacswiki.org/emacs/ELPA][package.el]] - =[built-in]= Install and manage Emacs packages easily.
     - [[https://github.com/Bruce-Connor/paradox][paradox]] - Modernizing Emacs' Package Menu with package ratings, usage statistics, customizability & more.
   - [[https://github.com/dimitri/el-get][el-get]] - apt-get style Emacs packages manager.
   - [[https://github.com/cask/cask][cask]] - Manage dependencies for your local Emacs configuration and automate the package development cycle.
     - [[https://github.com/rdallasgray/pallet][pallet]] - A package management tool for Emacs, built on Cask.
   - [[https://github.com/quelpa/quelpa][quelpa]] - Build and install your Emacs Lisp packages on-the-fly directly from source.

** Library

   - [[https://github.com/magnars/dash.el][dash.el]] - A modern list library.
   - [[https://github.com/magnars/s.el][s.el]] - String manipulation library.
   - [[https://github.com/rejeep/f.el][f.el]] - Modern API for working with files and directories in Emacs.
   - [[https://github.com/d11wtq/grizzl][Grizzl]] - A small utility library to be used in other Elisp code needing fuzzy search behaviour.

** Appearance

   - [[https://github.com/unic0rn/powerline][powerline]] - Emacs version of the Vim powerline.
   - [[https://github.com/raugturi/powerline-evil][powerline-evil]] - Utilities for better [[http://gitorious.org/evil/pages/Home][Evil]] support for Powerline.
   - [[https://github.com/Bruce-Connor/smart-mode-line][smart-mode-line]] - A sexy mode-line for Emacs.

** Theme

   - [[https://github.com/bbatsov/zenburn-emacs][Zenburn]] - /(dark)/ Vim's "Zenburn theme" ported to Emacs.
   - [[https://github.com/bbatsov/solarized-emacs][Solarized]] - /(light/dark)/ Solarized color theme.
   - [[https://github.com/purcell/color-theme-sanityinc-tomorrow][Sanityinc-tomorrow]] - /(light/dark)/ An Emacs version of "Tomorrow-themes".
   - [[https://github.com/oneKelvinSmith/monokai-emacs][Monokai]] - /(dark)/ A port of the popular TextMate theme Monokai
   - [[https://github.com/n3mo/cyberpunk-theme.el][Cyberpunk-theme]] - /(dark)/ *[256color]* Mostly a direct port of the "Cyberpunk Overtone theme".
   - [[https://github.com/jordonbiondo/ample-theme][Ample-theme]] - /(light/dark)/ *[256color]* A low-contrast theme for Emacs.
   - [[https://github.com/kuanyui/moe-theme.el][Moe-theme]]- /(light/dark)/ *[256color]* A customizable colorful eye-candy theme. Moe, moe, kyun!
   - [[https://github.com/fniessen/emacs-leuven-theme][Leuven-theme]] - =[built-in]= /(light)/ Awesome Emacs color theme for white backgrounds
   - [[https://github.com/steckerhalter/grandshell-theme][Grandshell-theme]] - /(dark)/ *[256color]* Theme with intensive colors.

   #+BEGIN_QUOTE
   Above list is some of the most popular/installed themes. If still unsatisfied, you also can take a look of [[http://emacsthemes.caisah.info/][GNU Emacs Themes Gallery]] for screenshots of almost all available Emacs themes.
   #+END_QUOTE

** Fun

   - [[http://nyan-mode.buildsomethingamazing.com/][Nyan-mode]] - Let Nyan Cat show you your buffer position in mode line.
   - [[http://www.emacswiki.org/emacs/ZoneMode][Zone Mode]] - =[built-in]= A buffer obfuscator, or a screensaver.
   - [[http://www.cb1.com/~john/computing/emacs/lisp/games/index.html][swimmers.el]] - An emacs screensaver.

** Starter Kit

   - [[https://github.com/bbatsov/prelude][Prelude]] - Prelude is an enhanced Emacs 24 distribution that should make your experience with Emacs both more pleasant and more powerful.
   - [[https://github.com/overtone/emacs-live][Emacs-live]] - M-x start-hacking http://overtone.github.com/emacs-live/ .
   - [[https://github.com/purcell/emacs.d][Purcell's .emacs.d]] - An Emacs configuration bundle with batteries included.
   - [[https://github.com/eschulte/emacs24-starter-kit][Emacs24 Starter Kit]] - A cleaner version of the literate starter kit based on Emacs24 http://eschulte.github.com/emacs24-starter-kit/ .
   - [[https://github.com/xiaohanyu/oh-my-emacs][Oh-My-Emacs]] - Provide an awesome, out-of-box, literate dotemacs for both newbies and nerds. http://xiaohanyu.github.io/oh-my-emacs .
   - [[https://github.com/senny/cabbage][Cabbage]] - Get the maximum out of emacs http://senny.github.com/cabbage/ .
   - [[https://github.com/syl20bnr/spacemacs][Spacemacs]] - A slick Evil focused starter kit: do not fear RSI anymore.
   - [[https://github.com/rdallasgray/graphene][Graphene]] - A set of defaults for Emacs, for refugees from GUI text editors.

* Contributing

Your contributions are always welcome! Please submit a pull request or create an issue to add a new package, library or software to the list.

** Generate "Table of Contents"
After editing and going to commit & push this list, you can use `/gen-toc.el` to update the table of contents with =M-x awesome-emacs-gen-toc= in =README.org= buffer.

** Emacs Built-In Packages
If a package is available in latest Emacs, please remember to add a =[built-in]= tag in the front of description.

