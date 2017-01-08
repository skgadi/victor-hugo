+++
#SEO Data
Keywords = ["research", "publications", "articles", "conference"]
description = "Suresh Kumar Gadi has contributions in 1 journal article and 5 conference proceedings."
date = "1999-06-01T00:00:00+05:30"
title = "Research"

+++
<h1 class="header">Publications</h1>

<div>
<div class="container-fluid">
	<div class="searchbar">
		<input style="width: 100%;"type="text" class="Authrozed bibtex_search form-control SKGSearchItem" id="searchbar" placeholder="Search - Example: journal 2015 (finds the intersection of the two terms)"/>
		<br/><br/>
	<table style="margin: auto;"><tr>
	<td>
		<select id="authorselectfirst" class="btn bibtex_search bibtex_author ResearchSearchItem" extra="first" search="author">
			<option value="">Search First Author</option>
		</select>
	</td><td>
		<select id="authorselect" class="btn bibtex_search bibtex_author ResearchSearchItem" search="author">
			<option value="">Search Author</option>
		</select>
	</td><td>
		<select id="topicselect" class="btn bibtex_search ResearchSearchItem" >
			<option value="">Search Topic</option>
			<!-- Add topic values here -->
			<option value="force|torque|acceleration">Mechanical</option>
			<option value="electric|electrical|electronic|electronic|capacitor|solar|power|energy|voltage|current">Electrical & electronics</option>
			<option value="control|PID|stability|analysis">Control</option>
		</select>
	</td><td>
		<button type="button" class="btn btn-default ResearchSearchItem" onclick="reset()">Reset</button>
	</td>
	</tr></table>
	</div>
</div>
<br/>

<div class="bibtex_structure">
  <div class="group year" extra="ASC number">
  	  <!--a href="#top" style="display: inline"><em>(Top of the page)</em></a-->
  	  <div style="padding-bottom:10px;"></div>
  	  <div class="sort journal" extra="DESC string">
      	<div class="templates"></div>
      </div>
  </div>
</div>

<div id="bibtex_display">
		<div class="if bibtex_template" style="display: none;">
			<ul><li>
				<a class="SKGListItem" href="#PutHTMLHere" rel="modal:open"><span class="SKGListItem bibtexVar" id="bib+BIBTEXKEY+" extra="BIBTEXKEY" onclick="DisplayItem('BIBD+BIBTEXKEY+')">
					<span class="if title"><span class="title"></span>.</span>
					<span class="if author"><em><span class="author"></span></em>.</span>
					<span class="if edition">Edition: <span class="edition"></span>.</span>
					<span class="if year"><span class="year"></span>.</span>
				</span></a>
				<div style="display: none;" class="bibtexVar" id="BIBD+BIBTEXKEY+" extra="BIBTEXKEY">
			
					<div class="if title" ><h1 style=" font-weight: normal; text-align: center; margin: 0px;"><span class="title"></span></h1></div>
					<br/>
					<div class="if author"><h4 style=" font-weight: normal; text-align: center;  margin: 0px;"><span class="author"></span></h4></div>
					<div class="if organization"><h4 style=" font-weight: normal; text-align: center; margin: 0px;"><em><span class="organization"></span></em></h4></div>
					<div class="if booktitle"><h4 style=" font-weight: normal; text-align: center; margin: 0px;"><em><span class="booktitle"></span></em></h4></div>
					<br/>
					<div class="if abstract"><span style=" font-weight: bold; text-align: center; margin: 0px;">Abstract:&ndash; </span><span class="abstract" style=" font-weight: normal; text-align: justify;"></span></div>
					<br/>
					<b>More information:</b>
					<table class="ContentTable">
						<TR class="if address"><TD>Address</TD><TD><span class="address"></span></TD></TR>
						<TR class="if annote"><TD>Annote</TD><TD><span class="annote"></span></TD></TR>
						<TR class="if chapter"><TD>Chapter</TD><TD><span class="chapter"></span></TD></TR>
						<TR class="if crossref"><TD>Crossref</TD><TD><span class="crossref"></span></TD></TR>
						<TR class="if doi"><TD>DOI</TD><TD><span style="cursor: pointer;" class="doi" onclick="OpenDOI(this);"></span></TD></TR>
						<TR class="if edition"><TD>Edition</TD><TD><span class="edition"></span></TD></TR>
						<TR class="if editor"><TD>Editor</TD><TD><span class="editor"></span></TD></TR>
						<TR class="if howpublished"><TD>How published</TD><TD><span class="howpublished"></span></TD></TR>
						<TR class="if institution"><TD>Institution</TD><TD><span class="institution"></span></TD></TR>
						<TR class="if isbn"><TD>ISBN</TD><TD><span class="isbn"></span></TD></TR>
						<TR class="if journal"><TD>Journal</TD><TD><span class="journal"></span></TD></TR>
						<TR class="if key"><TD>Key</TD><TD><span class="key"></span></TD></TR>
						<TR class="if month"><TD>Month</TD><TD><span class="month"></span></TD></TR>
						<TR class="if note"><TD>Note</TD><TD><span class="note"></span></TD></TR>
						<TR class="if number"><TD>Number</TD><TD><span class="number"></span></TD></TR>
						<TR class="if pages"><TD>Pages</TD><TD><span class="pages"></span></TD></TR>
						<TR class="if publisher"><TD>Publisher</TD><TD><span class="publisher"></span></TD></TR>
						<TR class="if school"><TD>School</TD><TD><span class="school"></span></TD></TR>
						<TR class="if series"><TD>Series</TD><TD><span class="series"></span></TD></TR>
						<TR class="if type"><TD>Type</TD><TD><span class="type"></span></TD></TR>
						<TR class="if url"><TD>URL</TD><TD><span style="cursor: pointer;" class="url" onclick="OpenURL(this);"></span></TD></TR>
						<TR class="if volume"><TD>Volume</TD><TD><span class="volume"></span></TD></TR>
						<TR class="if year"><TD>Year</TD><TD><span class="year"></span></TD></TR>
					</table>
					<br/>
					<div style="position: relative;">
					<pre class = "BibTeXRawCodeBlock" onclick="SelectTheText(this)" ondblclick="CopyTheText(this);"><span class="bibtexraw noread"></span></pre>
					<a class="Icon" style="display: float;position: absolute; bottom: 0px; right: 5px; font-size: 40px; cursor: pointer;" onclick="CopyThePrevText(this)">&#x2398;</a>
					</div>
				</div>
			</li></ul>
		</div>
</div>
<div class="modal" id="PutHTMLHere" style= "width: 100%; display: none;" >Select an entry to view the complete details here.</div>
</div>