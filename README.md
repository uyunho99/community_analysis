# Community Analysis

## Introduction

This repository is dedicated to enhancing the outreach of deep daiv.'s AI-related content across various social media platforms, with a focus on the developer community site "Careerly". Our goal is to understand what makes AI knowledge content engaging and effective, thereby improving the sustainability and reach of our content.

## Our analysis focuses on two Key Performance Indicators (KPIs):

Primary KPI: 크리에이터(작가), 글의 제목, 크리에이터의 업로드 주기, 썸네일 내용(커리어리에서는 첫 번째 문단 등)
Secondary KPI: 좋아요, 공유, 스크랩, 댓글
We employ text mining and time series analysis to understand the impact of various factors on content engagement.

## Dataset

| Field     | Type     | Description                 |
| --------- | -------- | --------------------------- |
| 제목      | String   | 콘텐츠의 제목               |
| 글쓴이    | String   | 콘텐츠를 작성한 작가의 이름 |
| 글        | String   | 콘텐츠 본문                 |
| 게시 날짜 | Datetime | 콘텐츠가 게시된 날짜        |
| 조회 수   | Integer  | 콘텐츠가 조회된 횟수        |
| 좋아요 수 | Integer  | 콘텐츠에 대한 좋아요 수     |
| 공유 수   | Integer  | 콘텐츠가 공유된 횟수        |
| 저장 수   | Integer  | 콘텐츠가 저장된 횟수        |
| 댓글 수   | Integer  | 콘텐츠에 달린 댓글 수       |
| 분야      | String   | 콘텐츠가 속한 분야          |
