# Data Anonymization Competition
# iPWS Cup 2024

## What's new
- June 20th, 2024: Opened this page.

## Useful links for competitions
- TBA

## About iPWS Cup 2024
### Story
Company A wants to develop a movie recommendation system using customer data and decides to anonymize customer data for a competition to develop a recommendation system and make it available to the participants of the competition. However, even with the intention of anonymizing the data, there have been cases of personal identification and privacy breaches due to matching with external data. More recently, there has also been the problem of "database reconstruction attacks", where even anonymized data and can be combined with supposedly secure statistical data to reconstruct the original data. Can Company A create highly useful anonymized data while preventing personal identification attacks and database reconstruction attacks?

### Competition Overview
Each participating team takes on the roles of both anonymizer and attacker, competing in data anonymizing techniques and attacks on the anonymized data. In data anonymization phase, each team takes the role of a company that wants to publish customer data, and aims to protect the privacy of the people in the data by anonymizing the given data. In attack phase, each team becomes an attacker who wants to discover the contents of the data, and aims to discover more secret information about the individual contained in the data anonymized by other teams.

### Procedure
The competition consists of two phases.
Anonymization Phase: Each team will produce a set of anonymized data from fictitious data on movie ratings (each anonymized data will be processed from original multi-attribute data, from which only the attributes necessary for analysis will be extracted). The anonymized data must be processed in a way that makes it difficult for others to identify the original information, with as little loss of utility as possible.
Attack Phase: Each team restores the values of the original data, some of which have been redacted by the other team, using anonymized data (database reconstruction attack). They also try to identify individuals by linking the original data, from which names etc. have been removed, to their names etc. using anonymized data.
After these have been performed in turn, the results of each team's anonymization and attacks will be evaluated by the organizer. The anonymization is evaluated in terms of the closeness of the analysis results obtained from the anonymized and original data (the closer, the better) and the difficulty of correctly guessing the secret data of the other team (the more difficult, the better), while the attack is evaluated in terms of the accuracy of the guesses made by the other team on the anonymized data (the more accurate, the better).

## iPWS Cup 2024 schedule (tentative)
<table border="0">
<tr><td> <strong>Date</strong> </td><td> <strong>Event</strong> </td></tr>
<tr><td> July 12th(Fri) - 24th(Wed), 2024</td> <td> Team registration </td></tr>
<tr><td> July 26th(Fri) - August 16th(Fri), 2024</td> <td> Anonymization phase</td></tr>
<tr><td> August 20th(Tue) - September 10th(Tue), 2024</td> <td> Attack phase</td></tr>
<tr><td> September 20th(Fri), 2024</td> <td> Final presentation in Kyoto, Japan</td></tr>
</td></tr>
</table>

## Committee
<dl>
 <dt>Chair</dt>
 <dd>Koji Chida, Gunma University, Japan</dd>
<dt>Members</dt>
 <dd>Masahiro Fujita, Mitsubishi Electric, Japan</dd>
 <dd>Makoto Iguchi, Kii, Japan</dd>
 <dd>Hiroaki Kikuchi, Meiji University, Japan</dd>
 <dd>Ruiqiang Ma, Inner Mongolia University of Technology, China</dd>
 <dd>Takayuki Miura, NTT, Japan</dd>
 <dd>Yuichi Nakamura, Softbank, Japan</dd>
</dl>

## Contact
iPWS Cup Inquiry

ipwscup2024-inquiry(at)csec.ipsj.or.jp (replace (at) with @)