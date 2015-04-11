latex_template_for_book
----------------
This is a template of latex syntax for writing book.

Build Up Enviroment
----------------
[ArchLinux] 
Please install following package:

     pacman -S --noconfirm texlive-most        # For latex's enviroment
     pacman -S --noconfirm texlive-langchinese # For latex language, Chinese package
     pacman -S --noconfirm texlive-publishers  # For TeX Live - LaTeX classes and packages for specific publishers
     
[Ubuntu] 
Please install following package:

     sudo apt-get --yes --force-yes install texlive
     sudo apt-get --yes --force-yes install texlive-xetex
     sudo apt-get --yes --force-yes install latex-cjk-all
     sudo apt-get --yes --force-yes install texlive-publishers

Compile 
----------------

     Type "make" then start to compile, then create a pdf file.
