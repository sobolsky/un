---
layout: default
title: Anatomy of Solidarity
description: Anatomy of Solidarity in UN Voting
show_downloads: false
google_analytics:
theme: jekyll-theme-cayman
---
[Anatomy of Solidarity in UN Voting](./)

## Profiles
> ### Voting Profile 
> The `Voting Profile` for each country will be called a simple sequence, consisting of -1, 0, 1, and n, reflecting the country’s position on each vote. The length of such a sequence for each country is the same and equals the number of resolutions on the voting topic. 
>
>I n the `Voting Profile`, these symbols are arranged in chronological order, starting with the result of the earlier resolution and ending with the result of the later one. 
>> ### Complete Voting Profil
>> This is a `Voting Profile` in which there is no *'n'* (abstention from voting).
>
>> ### Incomplete Voting Profile
>> This is a `Voting Profile` in which there is one or more *'n'* (abstention from voting).

> ### Voting Participation Degree
> This is a number from 0 to 1, where 0 corresponds to the `Voting Profile` of a country that did not participate in any of the votes, and 1 corresponds to the profile of a country with a `Complete Voting Profile`.
>
> The `Voting Participation Degree` is calculated as the ratio of the actual number of votes to the maximum possible. The `Voting Participation Degree` indicates the involvement of a particular country in the voting process on the topic.

## Groups
> ### Solidarity Group 
> These is group of countries that have at least one identical voting position. 
>> ### Complete Solidarity Group
>> Group consist of countries with identical `Complete Voting Profiles`. 
>
>> ### Partial Solidarity Group
>>The `Partial Solidarity Group` consists of countries with identical values in their `Solidarity Profiles` at corresponding positions, but not 'n'.
>
>> ### Threshold Solidarity Group
>> The `Threshold Solidarity Group` includes all countries with a `Solidarity Degree` value not equal to zero.

> ### Solidarity Degree
> The `Solidarity Degree` of a `Solidarity Group` is calculated as the ratio of the number of identical values in the Voting Profiles to the total number of votes, expressed both as a percentage and numerically (whole numbers from 1 to the total number of votes).

## Netsworks
> ### Solidarity Network
> The `Solidarity Network` is a network where the nodes represent voting participant countries, and the edges represent solidarity connections, with weights expressed in integer values of Solidarity Degree (whole numbers from 1 to the total number of resolutions)
>> ### Complete Solidarity Network
>> The `Complete Solidarity Network` is the `Solidarity Network` that includes all participating voting countries and visualizes edges with all possible values of Solidarity Degree between these countries.
>> ### 100% Solidarity Degree Network
>> The `100% Solidarity Degree Network` is the `Solidarity Network` that includes all participating voting countries and visualizes edges with Solidarity Degree values between these countries equal to 100% (weight = 1).


