---
layout: "single"
title: ""
#permalink: "/research/"
#author_profile: true

---

<script type="text/javascript">
   function toggleVisibility(block_id) {
       var e = document.getElementById(block_id);
       if(e.style.display == 'block')
          e.style.display = 'none';
       else
          e.style.display = 'block';
   }
    function copyToClip(element) {
        var str = document.getElementById(element).innerHTML;
        function listener(e) {
            e.clipboardData.setData("text/html", str);
            e.clipboardData.setData("text/plain", str);
            e.preventDefault();
        }
        document.addEventListener("copy", listener);
        document.execCommand("copy");
        document.removeEventListener("copy", listener);
};
</script>

# Publications

## Capturing Evolution in Word Usage: Just Add More Clusters?
*M Martinc, S Montariol, E Zosa and L Pivovarova*  
Temporal Web Workshop, Companion Proceedings of the Web Conference 2020.
<normal>
    <a href="https://arxiv.org/pdf/2001.06629.pdf" style="color:page.header.overlay_color">[PDF]</a>
    <a href="https://github.com/smontariol/AddMoreClusters" style="color:page.header.overlay_color">[GitHub]</a>
    <a style="color:page.header.overlay_color; cursor: pointer; cursor: hand;" onclick="toggleVisibility('bib_addmoreclusters');">[BibTeX]</a>
</normal>
<div id="bib_addmoreclusters" style="display:none;">
<small>
<a class="btn"  onclick="copyToClip('bib_addmoreclusters');">copy to clipboard</a>
<div class="highlighter-rouge"><pre id="bib_addmoreclusters" class="highlight">
@inproceedings{martinc2020capturing,
  title={Capturing Evolution in Word Usage: Just Add More Clusters?},
  author={Martinc, Matej and Montariol, Syrielle and Zosa, Elaine and Pivovarova, Lidia},
  booktitle={Companion Proceedings of the Web Conference 2020},
  pages={343--349},
  year={2020}
}
</pre></div></small>
</div>

## Studying semantic variations through several dimensions
*S Montariol and A Allauzen*  
27th conference of Traitement Automatique des Langues Naturelles (TALN 2020)
<normal>
    <a href="https://www.aclweb.org/anthology/2020.jeptalnrecital-taln.31.pdf" style="color:page.header.overlay_color">[PDF]</a>
    <a style="color:page.header.overlay_color; cursor: pointer; cursor: hand;" onclick="toggleVisibility('bib_taln20');">[BibTeX]</a>
</normal>
<div id="bib_taln20" style="display:none;">
<small>
<a class="btn"  onclick="copyToClip('bib_taln20');">copy to clipboard</a>
<div class="highlighter-rouge"><pre id="bib_taln20" class="highlight">
@inproceedings{montariol2020etude,
  title={Etude des variations sémantiques à travers plusieurs dimensions (Studying semantic variations through several dimensions)},
  author={Montariol, Syrielle and Allauzen, Alexandre},
  booktitle={Actes de la 27e conférence Traitement Automatique des Langues Naturelles (TALN)},
  pages={314--322},
  year={2020}
}

</pre></div></small>
</div>

## Variations in Word Usage for the Financial Domain
*S Montariol, A Allauzen and A Kitamoto*  
Second Workshop on Financial Technology and Natural Language Processing (FinNLP 2020)
<normal>
    <a href="https://www.aclweb.org/anthology/2020.finnlp-1.pdf#page=16" style="color:page.header.overlay_color">[PDF]</a>
    <a style="color:page.header.overlay_color; cursor: pointer; cursor: hand;" onclick="toggleVisibility('bib_finnlp1');">[BibTeX]</a>

</normal>
<div id="bib_finnlp1" style="display:none;">
<small>
<a class="btn"  onclick="copyToClip('bib_finnlp1');">copy to clipboard</a>
<div class="highlighter-rouge"><pre id="bib_finnlp1" class="highlight">
@inproceedings{montariol2020variations,
  title={Variations in Word Usage for the Financial Domain},
  author={Montariol, Syrielle and Allauzen, Alexandre and Kitamoto, Asanobu},
  booktitle={Proceedings of the Second Workshop on Financial Technology and Natural Language Processing},
  pages={8--14},
  year={2020}
}

</pre></div></small>
</div>

## Detecting Omissions of Risk Factors in Company Annual Reports
*C Masson and S Montariol*  
Second Workshop on Financial Technology and Natural Language Processing (FinNLP 2020)
<normal>
    <a href="https://www.aclweb.org/anthology/2020.finnlp-1.pdf#page=23" style="color:page.header.overlay_color">[PDF]</a>
    <a style="color:page.header.overlay_color; cursor: pointer; cursor: hand;" onclick="toggleVisibility('bib_finnlp2');">[BibTeX]</a>

</normal>
<div id="bib_finnlp2" style="display:none;">
<small>
<a class="btn"  onclick="copyToClip('bib_finnlp2');">copy to clipboard</a>
<div class="highlighter-rouge"><pre id="bib_finnlp2" class="highlight">
@inproceedings{masson2020detecting,
  title={Detecting Omissions of Risk Factors in Company Annual Reports},
  author={Masson, Corentin and Montariol, Syrielle},
  booktitle={Proceedings of the Second Workshop on Financial Technology and Natural Language Processing},
  pages={15--21},
  year={2020}
}
</pre></div></small>
</div>


## Empirical study of diachronic word embeddings for scarce data
*S Montariol and A Allauzen*  
International Conference on Recent Advances in Natural Language Processing (RANLP 2019)
<normal>
    <a href="https://www.aclweb.org/anthology/R19-1092.pdf" style="color:page.header.overlay_color">[PDF]</a>
    <a style="color:page.header.overlay_color; cursor: pointer; cursor: hand;" onclick="toggleVisibility('bib_ranlp19');">[BibTeX]</a>

</normal>
<div id="bib_ranlp19" style="display:none;">
<small>
<a class="btn"  onclick="copyToClip('bib_ranlp19');">copy to clipboard</a>
<div class="highlighter-rouge"><pre id="bib_ranlp19" class="highlight">
@InProceedings{Montariol2019,
  author    = {Montariol, Syrielle and Allauzen, Alexandre},
  title     = {Empirical Study of Diachronic Word Embeddings for Scarce Data},
  booktitle = {Proceedings of the International Conference on Recent Advances in Natural Language Processing (RANLP 2019)},
  year      = {2019},
  pages     = {795--803},
  address   = {Varna, Bulgaria},
  month     = sep,
  doi       = {10.26615/978-954-452-056-4_092},
}
</pre></div></small>
</div>


## Exploring sentence informativeness
*S Montariol, AG Soler and A Allauzen*  
26th conference of Traitement Automatique des Langues Naturelles (TALN 2019)
<normal>
    <a href="https://arxiv.org/pdf/1907.08469" style="color:page.header.overlay_color">[PDF]</a>
    <a style="color:page.header.overlay_color; cursor: pointer; cursor: hand;" onclick="toggleVisibility('bib_taln19_2');">[BibTeX]</a>

</normal>
<div id="bib_taln19_2" style="display:none;">
<small>
<a class="btn"  onclick="copyToClip('bib_taln19_2');">copy to clipboard</a>
<div class="highlighter-rouge"><pre id="bib_taln19_2" class="highlight">
@article{montariol2019exploring,
  title={Exploring sentence informativeness},
  author={Montariol, Syrielle and Soler, Aina Gari and Allauzen, Alexandre},
  journal={Actes de la 26e conférence de Traitement Automatique des Langues Naturelles (TALN)},
  year={2019}
}
</pre></div></small>
</div>


## Learning dynamic word embeddings with drift regularisation
*S Montariol and A Allauzen*  
Conférence Nationale d’Intelligence Artificielle 2019
<normal>
    <a href="https://hal.archives-ouvertes.fr/hal-02458049/file/OUN014%20-%20CNIA%202019%20V2.pdf#page=109" style="color:page.header.overlay_color">[PDF]</a>
    <a style="color:page.header.overlay_color; cursor: pointer; cursor: hand;" onclick="toggleVisibility('bib_taln19_1');">[BibTeX]</a>

</normal>
<div id="bib_taln19_1" style="display:none;">
<small>
<a class="btn"  onclick="copyToClip('bib_taln19_1');">copy to clipboard</a>
<div class="highlighter-rouge"><pre id="bib_taln19_1" class="highlight">
@article{montariol2019learning,
  title={Learning dynamic word embeddings with drift regularisation},
  author={Montariol, Syrielle and Allauzen, Alexandre},
  journal={Conférence Nationale d’Intelligence Artificielle 2019},
  pages={105},
  year={2019}
}





