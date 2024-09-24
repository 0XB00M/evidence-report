

<h1 style="text-align:center; font-weight:bold; font-size: 32px;">Web Application Firewall Reports</h1>


<PageBreak/>

# Table of Content

1. Objectives
2. Report<br/>
  2.1 Attack Protocols by Type<br>
  2.2 Top Hosts per Response Bytes<br>
  2.3 Bandwidth per Domain over Time<br>
  2.4 Top Hosts<br>
  2.5 All Hosts<br>
  2.6 Top Hosts per Domain over Time<br>
  2.7 Top Hits per Unique Src per Domain over Time<br>
  2.8 HTTP Methods over Time<br>
  2.9 Top HTTP Response Status Codes<br>
  2.10 Top 400 Response Status Codes per URL<br>
  2.11 Top 500 Response Status Codes per URL<br>
  2.12 Top HTTP Response Status Codes per Domain<br>
<!-- <ol>
  <li>1
    <ol>
      <li>&nbsp;&nbsp;1.1</li>
      <li>&nbsp;&nbsp;1.2</li>
    </ol>
  </li>
</ol> -->

Appendix A<br>
&nbsp;&nbsp;Devices (1)

Appendix B<br>
&nbsp;&nbsp;Report Filters(Logic: All)


<PageBreak/>

# 1. Objectives

The following reports provide insight into web application trends, behavior and consolidated view in a multi-FortiWeb environment

# 2. Reports

## 2.1 Top Attack Protocols by Type


Provides high level view web app usage with overall bandwidth overtime.

## 2.2 Top Hosts per Response Bytes

Detailed info regarding bandwidth use per host.

## 2.3 Bandwidth per Domain over Time

Breakdown of bandwidth used for each website, helps with identification of utilization patterns during the day.

## 2.4 Top Hosts

Top hosts per number of hits.

## 2.5 All Hosts


Detailed info regarding requested hosts and as a percentage of overall hits.

## 2.6 Top Hosts per Domain over Time


This can help to identify which sites are more active for each period of the day, which can help in capacity planning
and eventually creating a dynamic resource distribution in their server farm (moving resources from one website to
another during specific dates/times). Just like other trend graphs this can help security admins identify deviations in
a glimpse.

## 2.7 Top Hits per Unique Src per Domain over Time

This is an attempt to give the administrator a rough idea of "unique visitors". Given this is based on source IP, depending on the architecture could be more valuable to some customers than others.


## 2.8 HTTP Methods over Time


This chart gives insight into how HTTP methods are used overtime and can hint to orchestrated attacks when large
amount of requests using methods not seen previously, suddenly occur which may need to be closely reviewed by
the security team.

## 2.9 Top HTTP Response Status Codes

This graph can help administrator to visualize errors in the application behavior (cyclical loops, excessive server-side errors or broken pages), and attempts to circumvent the access controls employed by the website (e.g. too many Unauthorized/Forbidden codes).

## 2.10 Top 400 Response Status Codes per URL

This table enable an administrator to identify failures in the website code (like broken references) and specific pages
that are more problematic for developer's review.

## 2.11 Top 500 Response Status Codes per URL

This table allow an administrator to identify errors in the server-side, too many 500 errors may indicate some problems in the web server or the application.

## 2.12 Top HTTP Response Status Codes per Domain

Similar to the "HTTP Response Status Codes" but with a breakdown per domain to ease the identification of
abnormal behaviour in specific websites.


<PageBreak/>
Appendix A

Devices (1)

FortiWeb[root]


<PageBreak/>
Appendix B

Report Filters(Logic: All)