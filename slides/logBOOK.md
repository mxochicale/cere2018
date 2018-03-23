logBOOK
---



# TODO

* [ ] Correct the error in the compilation when using the image and resize utde image
	(added:20march2018,0152, sorted:?)





# SORTED

* [x] CHANGES in titlepage and closing page `beamertherehri.sty`

```
    \else%
        %{\usebeamerfont{subtitle}\usebeamercolor[fg]{subtitle}\insertsubtitle\par}%
        {\usebeamerfont{subtitle}\usebeamercolor[fg]{subtitle}  \href{https://twitter.com/CERE_Emotion}{\faTwitter @CERE\_Emotion} \#CERE2018 \par }%
        \vspace*{1mm}
    \fi%
```


(added/sorted: 23march2018)

* [x] Change the resolution of the images for background, logo
	(added:20march2018,0153, sorted:21march2018)

Modifying `beamerthemehri.sty` for text position in the titlepage

```
    % Add background to title page
    \AddToShipoutPictureFG*{\includegraphics[width=\paperwidth]{background}}
    \begin{minipage}[b][\paperheight]{\textwidth}
    \vspace*{5mm}
    \includegraphics[height=15mm]{logo}\par
    \vspace*{2mm}
    \ifx\insertsubtitle\@empty%
    \else%
        {\usebeamerfont{title}\usebeamercolor[fg]{title}\inserttitle\par}%
	\vspace*{2mm}
    \fi%
    \ifx\insertsubtitle\@empty%
    \else%
        {\usebeamerfont{subtitle}\usebeamercolor[fg]{subtitle}\insertsubtitle\par}%
        \vspace*{1mm}
    \fi%
    \ifx\insertdate\@empty%
    \else%
        {\usebeamerfont{date}\usebeamercolor[fg]{date}\insertdate\par}%
    \fi%



```


