<html lang="en" data-bs-theme="light">

<head>
    <meta charset="utf-8">
    <style>
        @charset "UTF-8";

        /*!
   * Bootstrap  v5.3.0 (https://getbootstrap.com/)
   * Copyright 2011-2023 The Bootstrap Authors
   * Licensed under MIT (https://github.com/twbs/bootstrap/blob/main/LICENSE)
   */
        :root,
        [data-bs-theme=light] {
            --bs-blue: #0d6efd;
            --bs-indigo: #6610f2;
            --bs-purple: #6f42c1;
            --bs-pink: #d63384;
            --bs-red: #dc3545;
            --bs-orange: #fd7e14;
            --bs-yellow: #ffc107;
            --bs-green: #198754;
            --bs-teal: #20c997;
            --bs-cyan: #0dcaf0;
            --bs-black: #000;
            --bs-white: #fff;
            --bs-gray: #6c757d;
            --bs-gray-dark: #343a40;
            --bs-gray-100: #f8f9fa;
            --bs-gray-200: #e9ecef;
            --bs-gray-300: #dee2e6;
            --bs-gray-400: #ced4da;
            --bs-gray-500: #adb5bd;
            --bs-gray-600: #6c757d;
            --bs-gray-700: #495057;
            --bs-gray-800: #343a40;
            --bs-gray-900: #212529;
            --bs-primary: #0d6efd;
            --bs-secondary: #6c757d;
            --bs-success: #198754;
            --bs-info: #0dcaf0;
            --bs-warning: #ffc107;
            --bs-danger: #dc3545;
            --bs-light: #f8f9fa;
            --bs-dark: #212529;
            --bs-primary-rgb: 13, 110, 253;
            --bs-secondary-rgb: 108, 117, 125;
            --bs-success-rgb: 25, 135, 84;
            --bs-info-rgb: 13, 202, 240;
            --bs-warning-rgb: 255, 193, 7;
            --bs-danger-rgb: 220, 53, 69;
            --bs-light-rgb: 248, 249, 250;
            --bs-dark-rgb: 33, 37, 41;
            --bs-primary-text-emphasis: #052c65;
            --bs-secondary-text-emphasis: #2b2f32;
            --bs-success-text-emphasis: #0a3622;
            --bs-info-text-emphasis: #055160;
            --bs-warning-text-emphasis: #664d03;
            --bs-danger-text-emphasis: #58151c;
            --bs-light-text-emphasis: #495057;
            --bs-dark-text-emphasis: #495057;
            --bs-primary-bg-subtle: #cfe2ff;
            --bs-secondary-bg-subtle: #e2e3e5;
            --bs-success-bg-subtle: #d1e7dd;
            --bs-info-bg-subtle: #cff4fc;
            --bs-warning-bg-subtle: #fff3cd;
            --bs-danger-bg-subtle: #f8d7da;
            --bs-light-bg-subtle: #fcfcfd;
            --bs-dark-bg-subtle: #ced4da;
            --bs-primary-border-subtle: #9ec5fe;
            --bs-secondary-border-subtle: #c4c8cb;
            --bs-success-border-subtle: #a3cfbb;
            --bs-info-border-subtle: #9eeaf9;
            --bs-warning-border-subtle: #ffe69c;
            --bs-danger-border-subtle: #f1aeb5;
            --bs-light-border-subtle: #e9ecef;
            --bs-dark-border-subtle: #adb5bd;
            --bs-white-rgb: 255, 255, 255;
            --bs-black-rgb: 0, 0, 0;
            --bs-font-sans-serif: system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", "Noto Sans", "Liberation Sans", Arial, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol", "Noto Color Emoji";
            --bs-font-monospace: SFMono-Regular, Menlo, Monaco, Consolas, "Liberation Mono", "Courier New", monospace;
            --bs-gradient: linear-gradient(180deg, rgba(255, 255, 255, 0.15), rgba(255, 255, 255, 0));
            --bs-body-font-family: var(--bs-font-sans-serif);
            --bs-body-font-size: 1rem;
            --bs-body-font-weight: 400;
            --bs-body-line-height: 1.5;
            --bs-body-color: #212529;
            --bs-body-color-rgb: 33, 37, 41;
            --bs-body-bg: #fff;
            --bs-body-bg-rgb: 255, 255, 255;
            --bs-emphasis-color: #000;
            --bs-emphasis-color-rgb: 0, 0, 0;
            --bs-secondary-color: rgba(33, 37, 41, 0.75);
            --bs-secondary-color-rgb: 33, 37, 41;
            --bs-secondary-bg: #e9ecef;
            --bs-secondary-bg-rgb: 233, 236, 239;
            --bs-tertiary-color: rgba(33, 37, 41, 0.5);
            --bs-tertiary-color-rgb: 33, 37, 41;
            --bs-tertiary-bg: #f8f9fa;
            --bs-tertiary-bg-rgb: 248, 249, 250;
            --bs-heading-color: inherit;
            --bs-link-color: #0d6efd;
            --bs-link-color-rgb: 13, 110, 253;
            --bs-link-decoration: underline;
            --bs-link-hover-color: #0a58ca;
            --bs-link-hover-color-rgb: 10, 88, 202;
            --bs-code-color: #d63384;
            --bs-highlight-bg: #fff3cd;
            --bs-border-width: 1px;
            --bs-border-style: solid;
            --bs-border-color: #dee2e6;
            --bs-border-color-translucent: rgba(0, 0, 0, 0.175);
            --bs-border-radius: 0.375rem;
            --bs-border-radius-sm: 0.25rem;
            --bs-border-radius-lg: 0.5rem;
            --bs-border-radius-xl: 1rem;
            --bs-border-radius-xxl: 2rem;
            --bs-border-radius-2xl: var(--bs-border-radius-xxl);
            --bs-border-radius-pill: 50rem;
            --bs-box-shadow: 0 0.5rem 1rem rgba(0, 0, 0, 0.15);
            --bs-box-shadow-sm: 0 0.125rem 0.25rem rgba(0, 0, 0, 0.075);
            --bs-box-shadow-lg: 0 1rem 3rem rgba(0, 0, 0, 0.175);
            --bs-box-shadow-inset: inset 0 1px 2px rgba(0, 0, 0, 0.075);
            --bs-focus-ring-width: 0.25rem;
            --bs-focus-ring-opacity: 0.25;
            --bs-focus-ring-color: rgba(13, 110, 253, 0.25);
            --bs-form-valid-color: #198754;
            --bs-form-valid-border-color: #198754;
            --bs-form-invalid-color: #dc3545;
            --bs-form-invalid-border-color: #dc3545
        }

        [data-bs-theme=dark] {
            --color-scheme: dark;
            --bs-body-color: #adb5bd;
            --bs-body-color-rgb: 173, 181, 189;
            --bs-body-bg: #212529;
            --bs-body-bg-rgb: 33, 37, 41;
            --bs-emphasis-color: #fff;
            --bs-emphasis-color-rgb: 255, 255, 255;
            --bs-secondary-color: rgba(173, 181, 189, 0.75);
            --bs-secondary-color-rgb: 173, 181, 189;
            --bs-secondary-bg: #343a40;
            --bs-secondary-bg-rgb: 52, 58, 64;
            --bs-tertiary-color: rgba(173, 181, 189, 0.5);
            --bs-tertiary-color-rgb: 173, 181, 189;
            --bs-tertiary-bg: #2b3035;
            --bs-tertiary-bg-rgb: 43, 48, 53;
            --bs-primary-text-emphasis: #6ea8fe;
            --bs-secondary-text-emphasis: #a7acb1;
            --bs-success-text-emphasis: #75b798;
            --bs-info-text-emphasis: #6edff6;
            --bs-warning-text-emphasis: #ffda6a;
            --bs-danger-text-emphasis: #ea868f;
            --bs-light-text-emphasis: #f8f9fa;
            --bs-dark-text-emphasis: #dee2e6;
            --bs-primary-bg-subtle: #031633;
            --bs-secondary-bg-subtle: #161719;
            --bs-success-bg-subtle: #051b11;
            --bs-info-bg-subtle: #032830;
            --bs-warning-bg-subtle: #332701;
            --bs-danger-bg-subtle: #2c0b0e;
            --bs-light-bg-subtle: #343a40;
            --bs-dark-bg-subtle: #1a1d20;
            --bs-primary-border-subtle: #084298;
            --bs-secondary-border-subtle: #41464b;
            --bs-success-border-subtle: #0f5132;
            --bs-info-border-subtle: #087990;
            --bs-warning-border-subtle: #997404;
            --bs-danger-border-subtle: #842029;
            --bs-light-border-subtle: #495057;
            --bs-dark-border-subtle: #343a40;
            --bs-heading-color: inherit;
            --bs-link-color: #6ea8fe;
            --bs-link-hover-color: #8bb9fe;
            --bs-link-color-rgb: 110, 168, 254;
            --bs-link-hover-color-rgb: 139, 185, 254;
            --bs-code-color: #e685b5;
            --bs-border-color: #495057;
            --bs-border-color-translucent: rgba(255, 255, 255, 0.15);
            --bs-form-valid-color: #75b798;
            --bs-form-valid-border-color: #75b798;
            --bs-form-invalid-color: #ea868f;
            --bs-form-invalid-border-color: #ea868f
        }

        *,
        ::after,
        ::before {
            box-sizing: border-box
        }

        @media (prefers-reduced-motion:no-preference) {
            :root {
                scroll-behavior: smooth
            }
        }

        body {
            margin: 0;
            font-family: var(--bs-body-font-family);
            font-size: var(--bs-body-font-size);
            font-weight: var(--bs-body-font-weight);
            line-height: var(--bs-body-line-height);
            color: var(--bs-body-color);
            text-align: var(--bs-body-text-align);
            background-color: var(--bs-body-bg);
            -webkit-text-size-adjust: 100%;
            -webkit-tap-highlight-color: transparent
        }

        hr {
            margin: 1rem 0;
            color: inherit;
            border: 0;
            border-top: var(--bs-border-width) solid;
            opacity: .25
        }

        .h1,
        .h2,
        .h3,
        .h4,
        .h5,
        .h6,
        h1,
        h2,
        h3,
        h4,
        h5,
        h6 {
            margin-top: 0;
            margin-bottom: .5rem;
            font-weight: 500;
            line-height: 1.2;
            color: var(--bs-heading-color)
        }

        .h1,
        h1 {
            font-size: calc(1.375rem + 1.5vw)
        }

        @media (min-width:1200px) {

            .h1,
            h1 {
                font-size: 2.5rem
            }
        }

        .h2,
        h2 {
            font-size: calc(1.325rem + .9vw)
        }

        @media (min-width:1200px) {

            .h2,
            h2 {
                font-size: 2rem
            }
        }

        .h3,
        h3 {
            font-size: calc(1.3rem + .6vw)
        }

        @media (min-width:1200px) {

            .h3,
            h3 {
                font-size: 1.75rem
            }
        }

        .h4,
        h4 {
            font-size: calc(1.275rem + .3vw)
        }

        @media (min-width:1200px) {

            .h4,
            h4 {
                font-size: 1.5rem
            }
        }

        .h5,
        h5 {
            font-size: 1.25rem
        }

        .h6,
        h6 {
            font-size: 1rem
        }

        p {
            margin-top: 0;
            margin-bottom: 1rem
        }

        abbr[title] {
            -webkit-text-decoration: underline dotted;
            text-decoration: underline dotted;
            cursor: help;
            -webkit-text-decoration-skip-ink: none;
            text-decoration-skip-ink: none
        }

        address {
            margin-bottom: 1rem;
            font-style: normal;
            line-height: inherit
        }

        ol,
        ul {
            padding-left: 2rem
        }

        dl,
        ol,
        ul {
            margin-top: 0;
            margin-bottom: 1rem
        }

        ol ol,
        ol ul,
        ul ol,
        ul ul {
            margin-bottom: 0
        }

        dt {
            font-weight: 700
        }

        dd {
            margin-bottom: .5rem;
            margin-left: 0
        }

        blockquote {
            margin: 0 0 1rem
        }

        b,
        strong {
            font-weight: bolder
        }

        .small,
        small {
            font-size: .875em
        }

        .mark,
        mark {
            padding: .1875em;
            background-color: var(--bs-highlight-bg)
        }

        sub,
        sup {
            position: relative;
            font-size: .75em;
            line-height: 0;
            vertical-align: baseline
        }

        sub {
            bottom: -.25em
        }

        sup {
            top: -.5em
        }

        a {
            color: rgba(var(--bs-link-color-rgb), var(--bs-link-opacity, 1));
            text-decoration: underline
        }

        a:hover {
            --bs-link-color-rgb: var(--bs-link-hover-color-rgb)
        }

        a:not([href]):not([class]),
        a:not([href]):not([class]):hover {
            color: inherit;
            text-decoration: none
        }

        code,
        kbd,
        pre,
        samp {
            font-family: var(--bs-font-monospace);
            font-size: 1em
        }

        pre {
            display: block;
            margin-top: 0;
            margin-bottom: 1rem;
            overflow: auto;
            font-size: .875em
        }

        pre code {
            font-size: inherit;
            color: inherit;
            word-break: normal
        }

        code {
            font-size: .875em;
            color: var(--bs-code-color);
            word-wrap: break-word
        }

        a>code {
            color: inherit
        }

        kbd {
            padding: .1875rem .375rem;
            font-size: .875em;
            color: var(--bs-body-bg);
            background-color: var(--bs-body-color);
            border-radius: .25rem
        }

        kbd kbd {
            padding: 0;
            font-size: 1em
        }

        figure {
            margin: 0 0 1rem
        }

        img,
        svg {
            vertical-align: middle
        }

        table {
            caption-side: bottom;
            border-collapse: collapse
        }

        caption {
            padding-top: .5rem;
            padding-bottom: .5rem;
            color: var(--bs-secondary-color);
            text-align: left
        }

        th {
            text-align: inherit;
            text-align: -webkit-match-parent
        }

        tbody,
        td,
        tfoot,
        th,
        thead,
        tr {
            border-color: inherit;
            border-style: solid;
            border-width: 0
        }

        label {
            display: inline-block
        }

        button {
            border-radius: 0
        }

        button:focus:not(:focus-visible) {
            outline: 0
        }

        button,
        input,
        optgroup,
        select,
        textarea {
            margin: 0;
            font-family: inherit;
            font-size: inherit;
            line-height: inherit
        }

        button,
        select {
            text-transform: none
        }

        [role=button] {
            cursor: pointer
        }

        select {
            word-wrap: normal
        }

        select:disabled {
            opacity: 1
        }

        [list]:not([type=date]):not([type=datetime-local]):not([type=month]):not([type=week]):not([type=time])::-webkit-calendar-picker-indicator {
            display: none !important
        }

        [type=button],
        [type=reset],
        [type=submit],
        button {
            -webkit-appearance: button
        }

        [type=button]:not(:disabled),
        [type=reset]:not(:disabled),
        [type=submit]:not(:disabled),
        button:not(:disabled) {
            cursor: pointer
        }

        ::-moz-focus-inner {
            padding: 0;
            border-style: none
        }

        textarea {
            resize: vertical
        }

        fieldset {
            min-width: 0;
            padding: 0;
            margin: 0;
            border: 0
        }

        legend {
            float: left;
            width: 100%;
            padding: 0;
            margin-bottom: .5rem;
            font-size: calc(1.275rem + .3vw);
            line-height: inherit
        }

        @media (min-width:1200px) {
            legend {
                font-size: 1.5rem
            }
        }

        legend+* {
            clear: left
        }

        ::-webkit-datetime-edit-day-field,
        ::-webkit-datetime-edit-fields-wrapper,
        ::-webkit-datetime-edit-hour-field,
        ::-webkit-datetime-edit-minute,
        ::-webkit-datetime-edit-month-field,
        ::-webkit-datetime-edit-text,
        ::-webkit-datetime-edit-year-field {
            padding: 0
        }

        ::-webkit-inner-spin-button {
            height: auto
        }

        [type=search] {
            outline-offset: -2px;
            -webkit-appearance: textfield
        }

        ::-webkit-search-decoration {
            -webkit-appearance: none
        }

        ::-webkit-color-swatch-wrapper {
            padding: 0
        }

        ::-webkit-file-upload-button {
            font: inherit;
            -webkit-appearance: button
        }

        ::file-selector-button {
            font: inherit;
            -webkit-appearance: button
        }

        output {
            display: inline-block
        }

        iframe {
            border: 0
        }

        summary {
            display: list-item;
            cursor: pointer
        }

        progress {
            vertical-align: baseline
        }

        [hidden] {
            display: none !important
        }

        .lead {
            font-size: 1.25rem;
            font-weight: 300
        }

        .display-1 {
            font-size: calc(1.625rem + 4.5vw);
            font-weight: 300;
            line-height: 1.2
        }

        @media (min-width:1200px) {
            .display-1 {
                font-size: 5rem
            }
        }

        .display-2 {
            font-size: calc(1.575rem + 3.9vw);
            font-weight: 300;
            line-height: 1.2
        }

        @media (min-width:1200px) {
            .display-2 {
                font-size: 4.5rem
            }
        }

        .display-3 {
            font-size: calc(1.525rem + 3.3vw);
            font-weight: 300;
            line-height: 1.2
        }

        @media (min-width:1200px) {
            .display-3 {
                font-size: 4rem
            }
        }

        .display-4 {
            font-size: calc(1.475rem + 2.7vw);
            font-weight: 300;
            line-height: 1.2
        }

        @media (min-width:1200px) {
            .display-4 {
                font-size: 3.5rem
            }
        }

        .display-5 {
            font-size: calc(1.425rem + 2.1vw);
            font-weight: 300;
            line-height: 1.2
        }

        @media (min-width:1200px) {
            .display-5 {
                font-size: 3rem
            }
        }

        .display-6 {
            font-size: calc(1.375rem + 1.5vw);
            font-weight: 300;
            line-height: 1.2
        }

        @media (min-width:1200px) {
            .display-6 {
                font-size: 2.5rem
            }
        }

        .list-unstyled {
            padding-left: 0;
            list-style: none
        }

        .list-inline {
            padding-left: 0;
            list-style: none
        }

        .list-inline-item {
            display: inline-block
        }

        .list-inline-item:not(:last-child) {
            margin-right: .5rem
        }

        .initialism {
            font-size: .875em;
            text-transform: uppercase
        }

        .blockquote {
            margin-bottom: 1rem;
            font-size: 1.25rem
        }

        .blockquote>:last-child {
            margin-bottom: 0
        }

        .blockquote-footer {
            margin-top: -1rem;
            margin-bottom: 1rem;
            font-size: .875em;
            color: #6c757d
        }

        .blockquote-footer::before {
            content: "— "
        }

        .img-fluid {
            max-width: 100%;
            height: auto
        }

        .img-thumbnail {
            padding: .25rem;
            background-color: var(--bs-body-bg);
            border: var(--bs-border-width) solid var(--bs-border-color);
            border-radius: var(--bs-border-radius);
            max-width: 100%;
            height: auto
        }

        .figure {
            display: inline-block
        }

        .figure-img {
            margin-bottom: .5rem;
            line-height: 1
        }

        .figure-caption {
            font-size: .875em;
            color: var(--bs-secondary-color)
        }

        .container,
        .container-fluid,
        .container-lg,
        .container-md,
        .container-sm,
        .container-xl,
        .container-xxl {
            --bs-gutter-x: 1.5rem;
            --bs-gutter-y: 0;
            width: 100%;
            padding-right: calc(var(--bs-gutter-x) * .5);
            padding-left: calc(var(--bs-gutter-x) * .5);
            margin-right: auto;
            margin-left: auto
        }

        @media (min-width:576px) {

            .container,
            .container-sm {
                max-width: 540px
            }
        }

        @media (min-width:768px) {

            .container,
            .container-md,
            .container-sm {
                max-width: 720px
            }
        }

        @media (min-width:992px) {

            .container,
            .container-lg,
            .container-md,
            .container-sm {
                max-width: 960px
            }
        }

        @media (min-width:1200px) {

            .container,
            .container-lg,
            .container-md,
            .container-sm,
            .container-xl {
                max-width: 1140px
            }
        }

        @media (min-width:1400px) {

            .container,
            .container-lg,
            .container-md,
            .container-sm,
            .container-xl,
            .container-xxl {
                max-width: 1320px
            }
        }

        :root {
            --bs-breakpoint-xs: 0;
            --bs-breakpoint-sm: 576px;
            --bs-breakpoint-md: 768px;
            --bs-breakpoint-lg: 992px;
            --bs-breakpoint-xl: 1200px;
            --bs-breakpoint-xxl: 1400px
        }

        .row {
            --bs-gutter-x: 1.5rem;
            --bs-gutter-y: 0;
            display: flex;
            flex-wrap: wrap;
            margin-top: calc(-1 * var(--bs-gutter-y));
            margin-right: calc(-.5 * var(--bs-gutter-x));
            margin-left: calc(-.5 * var(--bs-gutter-x))
        }

        .row>* {
            flex-shrink: 0;
            width: 100%;
            max-width: 100%;
            padding-right: calc(var(--bs-gutter-x) * .5);
            padding-left: calc(var(--bs-gutter-x) * .5);
            margin-top: var(--bs-gutter-y)
        }

        .col {
            flex: 1 0 0%
        }

        .row-cols-auto>* {
            flex: 0 0 auto;
            width: auto
        }

        .row-cols-1>* {
            flex: 0 0 auto;
            width: 100%
        }

        .row-cols-2>* {
            flex: 0 0 auto;
            width: 50%
        }

        .row-cols-3>* {
            flex: 0 0 auto;
            width: 33.3333333333%
        }

        .row-cols-4>* {
            flex: 0 0 auto;
            width: 25%
        }

        .row-cols-5>* {
            flex: 0 0 auto;
            width: 20%
        }

        .row-cols-6>* {
            flex: 0 0 auto;
            width: 16.6666666667%
        }

        .col-auto {
            flex: 0 0 auto;
            width: auto
        }

        .col-1 {
            flex: 0 0 auto;
            width: 8.33333333%
        }

        .col-2 {
            flex: 0 0 auto;
            width: 16.66666667%
        }

        .col-3 {
            flex: 0 0 auto;
            width: 25%
        }

        .col-4 {
            flex: 0 0 auto;
            width: 33.33333333%
        }

        .col-5 {
            flex: 0 0 auto;
            width: 41.66666667%
        }

        .col-6 {
            flex: 0 0 auto;
            width: 50%
        }

        .col-7 {
            flex: 0 0 auto;
            width: 58.33333333%
        }

        .col-8 {
            flex: 0 0 auto;
            width: 66.66666667%
        }

        .col-9 {
            flex: 0 0 auto;
            width: 75%
        }

        .col-10 {
            flex: 0 0 auto;
            width: 83.33333333%
        }

        .col-11 {
            flex: 0 0 auto;
            width: 91.66666667%
        }

        .col-12 {
            flex: 0 0 auto;
            width: 100%
        }

        .offset-1 {
            margin-left: 8.33333333%
        }

        .offset-2 {
            margin-left: 16.66666667%
        }

        .offset-3 {
            margin-left: 25%
        }

        .offset-4 {
            margin-left: 33.33333333%
        }

        .offset-5 {
            margin-left: 41.66666667%
        }

        .offset-6 {
            margin-left: 50%
        }

        .offset-7 {
            margin-left: 58.33333333%
        }

        .offset-8 {
            margin-left: 66.66666667%
        }

        .offset-9 {
            margin-left: 75%
        }

        .offset-10 {
            margin-left: 83.33333333%
        }

        .offset-11 {
            margin-left: 91.66666667%
        }

        .g-0,
        .gx-0 {
            --bs-gutter-x: 0
        }

        .g-0,
        .gy-0 {
            --bs-gutter-y: 0
        }

        .g-1,
        .gx-1 {
            --bs-gutter-x: 0.25rem
        }

        .g-1,
        .gy-1 {
            --bs-gutter-y: 0.25rem
        }

        .g-2,
        .gx-2 {
            --bs-gutter-x: 0.5rem
        }

        .g-2,
        .gy-2 {
            --bs-gutter-y: 0.5rem
        }

        .g-3,
        .gx-3 {
            --bs-gutter-x: 1rem
        }

        .g-3,
        .gy-3 {
            --bs-gutter-y: 1rem
        }

        .g-4,
        .gx-4 {
            --bs-gutter-x: 1.5rem
        }

        .g-4,
        .gy-4 {
            --bs-gutter-y: 1.5rem
        }

        .g-5,
        .gx-5 {
            --bs-gutter-x: 3rem
        }

        .g-5,
        .gy-5 {
            --bs-gutter-y: 3rem
        }

        @media (min-width:576px) {
            .col-sm {
                flex: 1 0 0%
            }

            .row-cols-sm-auto>* {
                flex: 0 0 auto;
                width: auto
            }

            .row-cols-sm-1>* {
                flex: 0 0 auto;
                width: 100%
            }

            .row-cols-sm-2>* {
                flex: 0 0 auto;
                width: 50%
            }

            .row-cols-sm-3>* {
                flex: 0 0 auto;
                width: 33.3333333333%
            }

            .row-cols-sm-4>* {
                flex: 0 0 auto;
                width: 25%
            }

            .row-cols-sm-5>* {
                flex: 0 0 auto;
                width: 20%
            }

            .row-cols-sm-6>* {
                flex: 0 0 auto;
                width: 16.6666666667%
            }

            .col-sm-auto {
                flex: 0 0 auto;
                width: auto
            }

            .col-sm-1 {
                flex: 0 0 auto;
                width: 8.33333333%
            }

            .col-sm-2 {
                flex: 0 0 auto;
                width: 16.66666667%
            }

            .col-sm-3 {
                flex: 0 0 auto;
                width: 25%
            }

            .col-sm-4 {
                flex: 0 0 auto;
                width: 33.33333333%
            }

            .col-sm-5 {
                flex: 0 0 auto;
                width: 41.66666667%
            }

            .col-sm-6 {
                flex: 0 0 auto;
                width: 50%
            }

            .col-sm-7 {
                flex: 0 0 auto;
                width: 58.33333333%
            }

            .col-sm-8 {
                flex: 0 0 auto;
                width: 66.66666667%
            }

            .col-sm-9 {
                flex: 0 0 auto;
                width: 75%
            }

            .col-sm-10 {
                flex: 0 0 auto;
                width: 83.33333333%
            }

            .col-sm-11 {
                flex: 0 0 auto;
                width: 91.66666667%
            }

            .col-sm-12 {
                flex: 0 0 auto;
                width: 100%
            }

            .offset-sm-0 {
                margin-left: 0
            }

            .offset-sm-1 {
                margin-left: 8.33333333%
            }

            .offset-sm-2 {
                margin-left: 16.66666667%
            }

            .offset-sm-3 {
                margin-left: 25%
            }

            .offset-sm-4 {
                margin-left: 33.33333333%
            }

            .offset-sm-5 {
                margin-left: 41.66666667%
            }

            .offset-sm-6 {
                margin-left: 50%
            }

            .offset-sm-7 {
                margin-left: 58.33333333%
            }

            .offset-sm-8 {
                margin-left: 66.66666667%
            }

            .offset-sm-9 {
                margin-left: 75%
            }

            .offset-sm-10 {
                margin-left: 83.33333333%
            }

            .offset-sm-11 {
                margin-left: 91.66666667%
            }

            .g-sm-0,
            .gx-sm-0 {
                --bs-gutter-x: 0
            }

            .g-sm-0,
            .gy-sm-0 {
                --bs-gutter-y: 0
            }

            .g-sm-1,
            .gx-sm-1 {
                --bs-gutter-x: 0.25rem
            }

            .g-sm-1,
            .gy-sm-1 {
                --bs-gutter-y: 0.25rem
            }

            .g-sm-2,
            .gx-sm-2 {
                --bs-gutter-x: 0.5rem
            }

            .g-sm-2,
            .gy-sm-2 {
                --bs-gutter-y: 0.5rem
            }

            .g-sm-3,
            .gx-sm-3 {
                --bs-gutter-x: 1rem
            }

            .g-sm-3,
            .gy-sm-3 {
                --bs-gutter-y: 1rem
            }

            .g-sm-4,
            .gx-sm-4 {
                --bs-gutter-x: 1.5rem
            }

            .g-sm-4,
            .gy-sm-4 {
                --bs-gutter-y: 1.5rem
            }

            .g-sm-5,
            .gx-sm-5 {
                --bs-gutter-x: 3rem
            }

            .g-sm-5,
            .gy-sm-5 {
                --bs-gutter-y: 3rem
            }
        }

        @media (min-width:768px) {
            .col-md {
                flex: 1 0 0%
            }

            .row-cols-md-auto>* {
                flex: 0 0 auto;
                width: auto
            }

            .row-cols-md-1>* {
                flex: 0 0 auto;
                width: 100%
            }

            .row-cols-md-2>* {
                flex: 0 0 auto;
                width: 50%
            }

            .row-cols-md-3>* {
                flex: 0 0 auto;
                width: 33.3333333333%
            }

            .row-cols-md-4>* {
                flex: 0 0 auto;
                width: 25%
            }

            .row-cols-md-5>* {
                flex: 0 0 auto;
                width: 20%
            }

            .row-cols-md-6>* {
                flex: 0 0 auto;
                width: 16.6666666667%
            }

            .col-md-auto {
                flex: 0 0 auto;
                width: auto
            }

            .col-md-1 {
                flex: 0 0 auto;
                width: 8.33333333%
            }

            .col-md-2 {
                flex: 0 0 auto;
                width: 16.66666667%
            }

            .col-md-3 {
                flex: 0 0 auto;
                width: 25%
            }

            .col-md-4 {
                flex: 0 0 auto;
                width: 33.33333333%
            }

            .col-md-5 {
                flex: 0 0 auto;
                width: 41.66666667%
            }

            .col-md-6 {
                flex: 0 0 auto;
                width: 50%
            }

            .col-md-7 {
                flex: 0 0 auto;
                width: 58.33333333%
            }

            .col-md-8 {
                flex: 0 0 auto;
                width: 66.66666667%
            }

            .col-md-9 {
                flex: 0 0 auto;
                width: 75%
            }

            .col-md-10 {
                flex: 0 0 auto;
                width: 83.33333333%
            }

            .col-md-11 {
                flex: 0 0 auto;
                width: 91.66666667%
            }

            .col-md-12 {
                flex: 0 0 auto;
                width: 100%
            }

            .offset-md-0 {
                margin-left: 0
            }

            .offset-md-1 {
                margin-left: 8.33333333%
            }

            .offset-md-2 {
                margin-left: 16.66666667%
            }

            .offset-md-3 {
                margin-left: 25%
            }

            .offset-md-4 {
                margin-left: 33.33333333%
            }

            .offset-md-5 {
                margin-left: 41.66666667%
            }

            .offset-md-6 {
                margin-left: 50%
            }

            .offset-md-7 {
                margin-left: 58.33333333%
            }

            .offset-md-8 {
                margin-left: 66.66666667%
            }

            .offset-md-9 {
                margin-left: 75%
            }

            .offset-md-10 {
                margin-left: 83.33333333%
            }

            .offset-md-11 {
                margin-left: 91.66666667%
            }

            .g-md-0,
            .gx-md-0 {
                --bs-gutter-x: 0
            }

            .g-md-0,
            .gy-md-0 {
                --bs-gutter-y: 0
            }

            .g-md-1,
            .gx-md-1 {
                --bs-gutter-x: 0.25rem
            }

            .g-md-1,
            .gy-md-1 {
                --bs-gutter-y: 0.25rem
            }

            .g-md-2,
            .gx-md-2 {
                --bs-gutter-x: 0.5rem
            }

            .g-md-2,
            .gy-md-2 {
                --bs-gutter-y: 0.5rem
            }

            .g-md-3,
            .gx-md-3 {
                --bs-gutter-x: 1rem
            }

            .g-md-3,
            .gy-md-3 {
                --bs-gutter-y: 1rem
            }

            .g-md-4,
            .gx-md-4 {
                --bs-gutter-x: 1.5rem
            }

            .g-md-4,
            .gy-md-4 {
                --bs-gutter-y: 1.5rem
            }

            .g-md-5,
            .gx-md-5 {
                --bs-gutter-x: 3rem
            }

            .g-md-5,
            .gy-md-5 {
                --bs-gutter-y: 3rem
            }
        }

        @media (min-width:992px) {
            .col-lg {
                flex: 1 0 0%
            }

            .row-cols-lg-auto>* {
                flex: 0 0 auto;
                width: auto
            }

            .row-cols-lg-1>* {
                flex: 0 0 auto;
                width: 100%
            }

            .row-cols-lg-2>* {
                flex: 0 0 auto;
                width: 50%
            }

            .row-cols-lg-3>* {
                flex: 0 0 auto;
                width: 33.3333333333%
            }

            .row-cols-lg-4>* {
                flex: 0 0 auto;
                width: 25%
            }

            .row-cols-lg-5>* {
                flex: 0 0 auto;
                width: 20%
            }

            .row-cols-lg-6>* {
                flex: 0 0 auto;
                width: 16.6666666667%
            }

            .col-lg-auto {
                flex: 0 0 auto;
                width: auto
            }

            .col-lg-1 {
                flex: 0 0 auto;
                width: 8.33333333%
            }

            .col-lg-2 {
                flex: 0 0 auto;
                width: 16.66666667%
            }

            .col-lg-3 {
                flex: 0 0 auto;
                width: 25%
            }

            .col-lg-4 {
                flex: 0 0 auto;
                width: 33.33333333%
            }

            .col-lg-5 {
                flex: 0 0 auto;
                width: 41.66666667%
            }

            .col-lg-6 {
                flex: 0 0 auto;
                width: 50%
            }

            .col-lg-7 {
                flex: 0 0 auto;
                width: 58.33333333%
            }

            .col-lg-8 {
                flex: 0 0 auto;
                width: 66.66666667%
            }

            .col-lg-9 {
                flex: 0 0 auto;
                width: 75%
            }

            .col-lg-10 {
                flex: 0 0 auto;
                width: 83.33333333%
            }

            .col-lg-11 {
                flex: 0 0 auto;
                width: 91.66666667%
            }

            .col-lg-12 {
                flex: 0 0 auto;
                width: 100%
            }

            .offset-lg-0 {
                margin-left: 0
            }

            .offset-lg-1 {
                margin-left: 8.33333333%
            }

            .offset-lg-2 {
                margin-left: 16.66666667%
            }

            .offset-lg-3 {
                margin-left: 25%
            }

            .offset-lg-4 {
                margin-left: 33.33333333%
            }

            .offset-lg-5 {
                margin-left: 41.66666667%
            }

            .offset-lg-6 {
                margin-left: 50%
            }

            .offset-lg-7 {
                margin-left: 58.33333333%
            }

            .offset-lg-8 {
                margin-left: 66.66666667%
            }

            .offset-lg-9 {
                margin-left: 75%
            }

            .offset-lg-10 {
                margin-left: 83.33333333%
            }

            .offset-lg-11 {
                margin-left: 91.66666667%
            }

            .g-lg-0,
            .gx-lg-0 {
                --bs-gutter-x: 0
            }

            .g-lg-0,
            .gy-lg-0 {
                --bs-gutter-y: 0
            }

            .g-lg-1,
            .gx-lg-1 {
                --bs-gutter-x: 0.25rem
            }

            .g-lg-1,
            .gy-lg-1 {
                --bs-gutter-y: 0.25rem
            }

            .g-lg-2,
            .gx-lg-2 {
                --bs-gutter-x: 0.5rem
            }

            .g-lg-2,
            .gy-lg-2 {
                --bs-gutter-y: 0.5rem
            }

            .g-lg-3,
            .gx-lg-3 {
                --bs-gutter-x: 1rem
            }

            .g-lg-3,
            .gy-lg-3 {
                --bs-gutter-y: 1rem
            }

            .g-lg-4,
            .gx-lg-4 {
                --bs-gutter-x: 1.5rem
            }

            .g-lg-4,
            .gy-lg-4 {
                --bs-gutter-y: 1.5rem
            }

            .g-lg-5,
            .gx-lg-5 {
                --bs-gutter-x: 3rem
            }

            .g-lg-5,
            .gy-lg-5 {
                --bs-gutter-y: 3rem
            }
        }

        @media (min-width:1200px) {
            .col-xl {
                flex: 1 0 0%
            }

            .row-cols-xl-auto>* {
                flex: 0 0 auto;
                width: auto
            }

            .row-cols-xl-1>* {
                flex: 0 0 auto;
                width: 100%
            }

            .row-cols-xl-2>* {
                flex: 0 0 auto;
                width: 50%
            }

            .row-cols-xl-3>* {
                flex: 0 0 auto;
                width: 33.3333333333%
            }

            .row-cols-xl-4>* {
                flex: 0 0 auto;
                width: 25%
            }

            .row-cols-xl-5>* {
                flex: 0 0 auto;
                width: 20%
            }

            .row-cols-xl-6>* {
                flex: 0 0 auto;
                width: 16.6666666667%
            }

            .col-xl-auto {
                flex: 0 0 auto;
                width: auto
            }

            .col-xl-1 {
                flex: 0 0 auto;
                width: 8.33333333%
            }

            .col-xl-2 {
                flex: 0 0 auto;
                width: 16.66666667%
            }

            .col-xl-3 {
                flex: 0 0 auto;
                width: 25%
            }

            .col-xl-4 {
                flex: 0 0 auto;
                width: 33.33333333%
            }

            .col-xl-5 {
                flex: 0 0 auto;
                width: 41.66666667%
            }

            .col-xl-6 {
                flex: 0 0 auto;
                width: 50%
            }

            .col-xl-7 {
                flex: 0 0 auto;
                width: 58.33333333%
            }

            .col-xl-8 {
                flex: 0 0 auto;
                width: 66.66666667%
            }

            .col-xl-9 {
                flex: 0 0 auto;
                width: 75%
            }

            .col-xl-10 {
                flex: 0 0 auto;
                width: 83.33333333%
            }

            .col-xl-11 {
                flex: 0 0 auto;
                width: 91.66666667%
            }

            .col-xl-12 {
                flex: 0 0 auto;
                width: 100%
            }

            .offset-xl-0 {
                margin-left: 0
            }

            .offset-xl-1 {
                margin-left: 8.33333333%
            }

            .offset-xl-2 {
                margin-left: 16.66666667%
            }

            .offset-xl-3 {
                margin-left: 25%
            }

            .offset-xl-4 {
                margin-left: 33.33333333%
            }

            .offset-xl-5 {
                margin-left: 41.66666667%
            }

            .offset-xl-6 {
                margin-left: 50%
            }

            .offset-xl-7 {
                margin-left: 58.33333333%
            }

            .offset-xl-8 {
                margin-left: 66.66666667%
            }

            .offset-xl-9 {
                margin-left: 75%
            }

            .offset-xl-10 {
                margin-left: 83.33333333%
            }

            .offset-xl-11 {
                margin-left: 91.66666667%
            }

            .g-xl-0,
            .gx-xl-0 {
                --bs-gutter-x: 0
            }

            .g-xl-0,
            .gy-xl-0 {
                --bs-gutter-y: 0
            }

            .g-xl-1,
            .gx-xl-1 {
                --bs-gutter-x: 0.25rem
            }

            .g-xl-1,
            .gy-xl-1 {
                --bs-gutter-y: 0.25rem
            }

            .g-xl-2,
            .gx-xl-2 {
                --bs-gutter-x: 0.5rem
            }

            .g-xl-2,
            .gy-xl-2 {
                --bs-gutter-y: 0.5rem
            }

            .g-xl-3,
            .gx-xl-3 {
                --bs-gutter-x: 1rem
            }

            .g-xl-3,
            .gy-xl-3 {
                --bs-gutter-y: 1rem
            }

            .g-xl-4,
            .gx-xl-4 {
                --bs-gutter-x: 1.5rem
            }

            .g-xl-4,
            .gy-xl-4 {
                --bs-gutter-y: 1.5rem
            }

            .g-xl-5,
            .gx-xl-5 {
                --bs-gutter-x: 3rem
            }

            .g-xl-5,
            .gy-xl-5 {
                --bs-gutter-y: 3rem
            }
        }

        @media (min-width:1400px) {
            .col-xxl {
                flex: 1 0 0%
            }

            .row-cols-xxl-auto>* {
                flex: 0 0 auto;
                width: auto
            }

            .row-cols-xxl-1>* {
                flex: 0 0 auto;
                width: 100%
            }

            .row-cols-xxl-2>* {
                flex: 0 0 auto;
                width: 50%
            }

            .row-cols-xxl-3>* {
                flex: 0 0 auto;
                width: 33.3333333333%
            }

            .row-cols-xxl-4>* {
                flex: 0 0 auto;
                width: 25%
            }

            .row-cols-xxl-5>* {
                flex: 0 0 auto;
                width: 20%
            }

            .row-cols-xxl-6>* {
                flex: 0 0 auto;
                width: 16.6666666667%
            }

            .col-xxl-auto {
                flex: 0 0 auto;
                width: auto
            }

            .col-xxl-1 {
                flex: 0 0 auto;
                width: 8.33333333%
            }

            .col-xxl-2 {
                flex: 0 0 auto;
                width: 16.66666667%
            }

            .col-xxl-3 {
                flex: 0 0 auto;
                width: 25%
            }

            .col-xxl-4 {
                flex: 0 0 auto;
                width: 33.33333333%
            }

            .col-xxl-5 {
                flex: 0 0 auto;
                width: 41.66666667%
            }

            .col-xxl-6 {
                flex: 0 0 auto;
                width: 50%
            }

            .col-xxl-7 {
                flex: 0 0 auto;
                width: 58.33333333%
            }

            .col-xxl-8 {
                flex: 0 0 auto;
                width: 66.66666667%
            }

            .col-xxl-9 {
                flex: 0 0 auto;
                width: 75%
            }

            .col-xxl-10 {
                flex: 0 0 auto;
                width: 83.33333333%
            }

            .col-xxl-11 {
                flex: 0 0 auto;
                width: 91.66666667%
            }

            .col-xxl-12 {
                flex: 0 0 auto;
                width: 100%
            }

            .offset-xxl-0 {
                margin-left: 0
            }

            .offset-xxl-1 {
                margin-left: 8.33333333%
            }

            .offset-xxl-2 {
                margin-left: 16.66666667%
            }

            .offset-xxl-3 {
                margin-left: 25%
            }

            .offset-xxl-4 {
                margin-left: 33.33333333%
            }

            .offset-xxl-5 {
                margin-left: 41.66666667%
            }

            .offset-xxl-6 {
                margin-left: 50%
            }

            .offset-xxl-7 {
                margin-left: 58.33333333%
            }

            .offset-xxl-8 {
                margin-left: 66.66666667%
            }

            .offset-xxl-9 {
                margin-left: 75%
            }

            .offset-xxl-10 {
                margin-left: 83.33333333%
            }

            .offset-xxl-11 {
                margin-left: 91.66666667%
            }

            .g-xxl-0,
            .gx-xxl-0 {
                --bs-gutter-x: 0
            }

            .g-xxl-0,
            .gy-xxl-0 {
                --bs-gutter-y: 0
            }

            .g-xxl-1,
            .gx-xxl-1 {
                --bs-gutter-x: 0.25rem
            }

            .g-xxl-1,
            .gy-xxl-1 {
                --bs-gutter-y: 0.25rem
            }

            .g-xxl-2,
            .gx-xxl-2 {
                --bs-gutter-x: 0.5rem
            }

            .g-xxl-2,
            .gy-xxl-2 {
                --bs-gutter-y: 0.5rem
            }

            .g-xxl-3,
            .gx-xxl-3 {
                --bs-gutter-x: 1rem
            }

            .g-xxl-3,
            .gy-xxl-3 {
                --bs-gutter-y: 1rem
            }

            .g-xxl-4,
            .gx-xxl-4 {
                --bs-gutter-x: 1.5rem
            }

            .g-xxl-4,
            .gy-xxl-4 {
                --bs-gutter-y: 1.5rem
            }

            .g-xxl-5,
            .gx-xxl-5 {
                --bs-gutter-x: 3rem
            }

            .g-xxl-5,
            .gy-xxl-5 {
                --bs-gutter-y: 3rem
            }
        }

        .table {
            --bs-table-color-type: initial;
            --bs-table-bg-type: initial;
            --bs-table-color-state: initial;
            --bs-table-bg-state: initial;
            --bs-table-color: var(--bs-body-color);
            --bs-table-bg: var(--bs-body-bg);
            --bs-table-border-color: var(--bs-border-color);
            --bs-table-accent-bg: transparent;
            --bs-table-striped-color: var(--bs-body-color);
            --bs-table-striped-bg: rgba(0, 0, 0, 0.05);
            --bs-table-active-color: var(--bs-body-color);
            --bs-table-active-bg: rgba(0, 0, 0, 0.1);
            --bs-table-hover-color: var(--bs-body-color);
            --bs-table-hover-bg: rgba(0, 0, 0, 0.075);
            width: 100%;
            margin-bottom: 1rem;
            vertical-align: top;
            border-color: var(--bs-table-border-color)
        }

        .table>:not(caption)>*>* {
            padding: .5rem .5rem;
            color: var(--bs-table-color-state, var(--bs-table-color-type, var(--bs-table-color)));
            background-color: var(--bs-table-bg);
            border-bottom-width: var(--bs-border-width);
            box-shadow: inset 0 0 0 9999px var(--bs-table-bg-state, var(--bs-table-bg-type, var(--bs-table-accent-bg)))
        }

        .table>tbody {
            vertical-align: inherit
        }

        .table>thead {
            vertical-align: bottom
        }

        .table-group-divider {
            border-top: calc(var(--bs-border-width) * 2) solid currentcolor
        }

        .caption-top {
            caption-side: top
        }

        .table-sm>:not(caption)>*>* {
            padding: .25rem .25rem
        }

        .table-bordered>:not(caption)>* {
            border-width: var(--bs-border-width) 0
        }

        .table-bordered>:not(caption)>*>* {
            border-width: 0 var(--bs-border-width)
        }

        .table-borderless>:not(caption)>*>* {
            border-bottom-width: 0
        }

        .table-borderless>:not(:first-child) {
            border-top-width: 0
        }

        .table-striped>tbody>tr:nth-of-type(odd)>* {
            --bs-table-color-type: var(--bs-table-striped-color);
            --bs-table-bg-type: var(--bs-table-striped-bg)
        }

        .table-striped-columns>:not(caption)>tr>:nth-child(2n) {
            --bs-table-color-type: var(--bs-table-striped-color);
            --bs-table-bg-type: var(--bs-table-striped-bg)
        }

        .table-active {
            --bs-table-color-state: var(--bs-table-active-color);
            --bs-table-bg-state: var(--bs-table-active-bg)
        }

        .table-hover>tbody>tr:hover>* {
            --bs-table-color-state: var(--bs-table-hover-color);
            --bs-table-bg-state: var(--bs-table-hover-bg)
        }

        .table-primary {
            --bs-table-color: #000;
            --bs-table-bg: #cfe2ff;
            --bs-table-border-color: #bacbe6;
            --bs-table-striped-bg: #c5d7f2;
            --bs-table-striped-color: #000;
            --bs-table-active-bg: #bacbe6;
            --bs-table-active-color: #000;
            --bs-table-hover-bg: #bfd1ec;
            --bs-table-hover-color: #000;
            color: var(--bs-table-color);
            border-color: var(--bs-table-border-color)
        }

        .table-secondary {
            --bs-table-color: #000;
            --bs-table-bg: #e2e3e5;
            --bs-table-border-color: #cbccce;
            --bs-table-striped-bg: #d7d8da;
            --bs-table-striped-color: #000;
            --bs-table-active-bg: #cbccce;
            --bs-table-active-color: #000;
            --bs-table-hover-bg: #d1d2d4;
            --bs-table-hover-color: #000;
            color: var(--bs-table-color);
            border-color: var(--bs-table-border-color)
        }

        .table-success {
            --bs-table-color: #000;
            --bs-table-bg: #d1e7dd;
            --bs-table-border-color: #bcd0c7;
            --bs-table-striped-bg: #c7dbd2;
            --bs-table-striped-color: #000;
            --bs-table-active-bg: #bcd0c7;
            --bs-table-active-color: #000;
            --bs-table-hover-bg: #c1d6cc;
            --bs-table-hover-color: #000;
            color: var(--bs-table-color);
            border-color: var(--bs-table-border-color)
        }

        .table-info {
            --bs-table-color: #000;
            --bs-table-bg: #cff4fc;
            --bs-table-border-color: #badce3;
            --bs-table-striped-bg: #c5e8ef;
            --bs-table-striped-color: #000;
            --bs-table-active-bg: #badce3;
            --bs-table-active-color: #000;
            --bs-table-hover-bg: #bfe2e9;
            --bs-table-hover-color: #000;
            color: var(--bs-table-color);
            border-color: var(--bs-table-border-color)
        }

        .table-warning {
            --bs-table-color: #000;
            --bs-table-bg: #fff3cd;
            --bs-table-border-color: #e6dbb9;
            --bs-table-striped-bg: #f2e7c3;
            --bs-table-striped-color: #000;
            --bs-table-active-bg: #e6dbb9;
            --bs-table-active-color: #000;
            --bs-table-hover-bg: #ece1be;
            --bs-table-hover-color: #000;
            color: var(--bs-table-color);
            border-color: var(--bs-table-border-color)
        }

        .table-danger {
            --bs-table-color: #000;
            --bs-table-bg: #f8d7da;
            --bs-table-border-color: #dfc2c4;
            --bs-table-striped-bg: #eccccf;
            --bs-table-striped-color: #000;
            --bs-table-active-bg: #dfc2c4;
            --bs-table-active-color: #000;
            --bs-table-hover-bg: #e5c7ca;
            --bs-table-hover-color: #000;
            color: var(--bs-table-color);
            border-color: var(--bs-table-border-color)
        }

        .table-light {
            --bs-table-color: #000;
            --bs-table-bg: #f8f9fa;
            --bs-table-border-color: #dfe0e1;
            --bs-table-striped-bg: #ecedee;
            --bs-table-striped-color: #000;
            --bs-table-active-bg: #dfe0e1;
            --bs-table-active-color: #000;
            --bs-table-hover-bg: #e5e6e7;
            --bs-table-hover-color: #000;
            color: var(--bs-table-color);
            border-color: var(--bs-table-border-color)
        }

        .table-dark {
            --bs-table-color: #fff;
            --bs-table-bg: #212529;
            --bs-table-border-color: #373b3e;
            --bs-table-striped-bg: #2c3034;
            --bs-table-striped-color: #fff;
            --bs-table-active-bg: #373b3e;
            --bs-table-active-color: #fff;
            --bs-table-hover-bg: #323539;
            --bs-table-hover-color: #fff;
            color: var(--bs-table-color);
            border-color: var(--bs-table-border-color)
        }

        .table-responsive {
            overflow-x: auto;
            -webkit-overflow-scrolling: touch
        }

        @media (max-width:575.98px) {
            .table-responsive-sm {
                overflow-x: auto;
                -webkit-overflow-scrolling: touch
            }
        }

        @media (max-width:767.98px) {
            .table-responsive-md {
                overflow-x: auto;
                -webkit-overflow-scrolling: touch
            }
        }

        @media (max-width:991.98px) {
            .table-responsive-lg {
                overflow-x: auto;
                -webkit-overflow-scrolling: touch
            }
        }

        @media (max-width:1199.98px) {
            .table-responsive-xl {
                overflow-x: auto;
                -webkit-overflow-scrolling: touch
            }
        }

        @media (max-width:1399.98px) {
            .table-responsive-xxl {
                overflow-x: auto;
                -webkit-overflow-scrolling: touch
            }
        }

        .form-label {
            margin-bottom: .5rem
        }

        .col-form-label {
            padding-top: calc(.375rem + var(--bs-border-width));
            padding-bottom: calc(.375rem + var(--bs-border-width));
            margin-bottom: 0;
            font-size: inherit;
            line-height: 1.5
        }

        .col-form-label-lg {
            padding-top: calc(.5rem + var(--bs-border-width));
            padding-bottom: calc(.5rem + var(--bs-border-width));
            font-size: 1.25rem
        }

        .col-form-label-sm {
            padding-top: calc(.25rem + var(--bs-border-width));
            padding-bottom: calc(.25rem + var(--bs-border-width));
            font-size: .875rem
        }

        .form-text {
            margin-top: .25rem;
            font-size: .875em;
            color: var(--bs-secondary-color)
        }

        .form-control {
            display: block;
            width: 100%;
            padding: .375rem .75rem;
            font-size: 1rem;
            font-weight: 400;
            line-height: 1.5;
            color: var(--bs-body-color);
            background-color: var(--bs-body-bg);
            background-clip: padding-box;
            border: var(--bs-border-width) solid var(--bs-border-color);
            -webkit-appearance: none;
            -moz-appearance: none;
            appearance: none;
            border-radius: var(--bs-border-radius);
            transition: border-color .15s ease-in-out, box-shadow .15s ease-in-out
        }

        @media (prefers-reduced-motion:reduce) {
            .form-control {
                transition: none
            }
        }

        .form-control[type=file] {
            overflow: hidden
        }

        .form-control[type=file]:not(:disabled):not([readonly]) {
            cursor: pointer
        }

        .form-control:focus {
            color: var(--bs-body-color);
            background-color: var(--bs-body-bg);
            border-color: #86b7fe;
            outline: 0;
            box-shadow: 0 0 0 .25rem rgba(13, 110, 253, .25)
        }

        .form-control::-webkit-date-and-time-value {
            min-width: 85px;
            height: 1.5em;
            margin: 0
        }

        .form-control::-webkit-datetime-edit {
            display: block;
            padding: 0
        }

        .form-control::-moz-placeholder {
            color: var(--bs-secondary-color);
            opacity: 1
        }

        .form-control::placeholder {
            color: var(--bs-secondary-color);
            opacity: 1
        }

        .form-control:disabled {
            background-color: var(--bs-secondary-bg);
            opacity: 1
        }

        .form-control::-webkit-file-upload-button {
            padding: .375rem .75rem;
            margin: -.375rem -.75rem;
            -webkit-margin-end: .75rem;
            margin-inline-end: .75rem;
            color: var(--bs-body-color);
            background-color: var(--bs-tertiary-bg);
            pointer-events: none;
            border-color: inherit;
            border-style: solid;
            border-width: 0;
            border-inline-end-width: var(--bs-border-width);
            border-radius: 0;
            -webkit-transition: color .15s ease-in-out, background-color .15s ease-in-out, border-color .15s ease-in-out, box-shadow .15s ease-in-out;
            transition: color .15s ease-in-out, background-color .15s ease-in-out, border-color .15s ease-in-out, box-shadow .15s ease-in-out
        }

        .form-control::file-selector-button {
            padding: .375rem .75rem;
            margin: -.375rem -.75rem;
            -webkit-margin-end: .75rem;
            margin-inline-end: .75rem;
            color: var(--bs-body-color);
            background-color: var(--bs-tertiary-bg);
            pointer-events: none;
            border-color: inherit;
            border-style: solid;
            border-width: 0;
            border-inline-end-width: var(--bs-border-width);
            border-radius: 0;
            transition: color .15s ease-in-out, background-color .15s ease-in-out, border-color .15s ease-in-out, box-shadow .15s ease-in-out
        }

        @media (prefers-reduced-motion:reduce) {
            .form-control::-webkit-file-upload-button {
                -webkit-transition: none;
                transition: none
            }

            .form-control::file-selector-button {
                transition: none
            }
        }

        .form-control:hover:not(:disabled):not([readonly])::-webkit-file-upload-button {
            background-color: var(--bs-secondary-bg)
        }

        .form-control:hover:not(:disabled):not([readonly])::file-selector-button {
            background-color: var(--bs-secondary-bg)
        }

        .form-control-plaintext {
            display: block;
            width: 100%;
            padding: .375rem 0;
            margin-bottom: 0;
            line-height: 1.5;
            color: var(--bs-body-color);
            background-color: transparent;
            border: solid transparent;
            border-width: var(--bs-border-width) 0
        }

        .form-control-plaintext:focus {
            outline: 0
        }

        .form-control-plaintext.form-control-lg,
        .form-control-plaintext.form-control-sm {
            padding-right: 0;
            padding-left: 0
        }

        .form-control-sm {
            min-height: calc(1.5em + .5rem + calc(var(--bs-border-width) * 2));
            padding: .25rem .5rem;
            font-size: .875rem;
            border-radius: var(--bs-border-radius-sm)
        }

        .form-control-sm::-webkit-file-upload-button {
            padding: .25rem .5rem;
            margin: -.25rem -.5rem;
            -webkit-margin-end: .5rem;
            margin-inline-end: .5rem
        }

        .form-control-sm::file-selector-button {
            padding: .25rem .5rem;
            margin: -.25rem -.5rem;
            -webkit-margin-end: .5rem;
            margin-inline-end: .5rem
        }

        .form-control-lg {
            min-height: calc(1.5em + 1rem + calc(var(--bs-border-width) * 2));
            padding: .5rem 1rem;
            font-size: 1.25rem;
            border-radius: var(--bs-border-radius-lg)
        }

        .form-control-lg::-webkit-file-upload-button {
            padding: .5rem 1rem;
            margin: -.5rem -1rem;
            -webkit-margin-end: 1rem;
            margin-inline-end: 1rem
        }

        .form-control-lg::file-selector-button {
            padding: .5rem 1rem;
            margin: -.5rem -1rem;
            -webkit-margin-end: 1rem;
            margin-inline-end: 1rem
        }

        textarea.form-control {
            min-height: calc(1.5em + .75rem + calc(var(--bs-border-width) * 2))
        }

        textarea.form-control-sm {
            min-height: calc(1.5em + .5rem + calc(var(--bs-border-width) * 2))
        }

        textarea.form-control-lg {
            min-height: calc(1.5em + 1rem + calc(var(--bs-border-width) * 2))
        }

        .form-control-color {
            width: 3rem;
            height: calc(1.5em + .75rem + calc(var(--bs-border-width) * 2));
            padding: .375rem
        }

        .form-control-color:not(:disabled):not([readonly]) {
            cursor: pointer
        }

        .form-control-color::-moz-color-swatch {
            border: 0 !important;
            border-radius: var(--bs-border-radius)
        }

        .form-control-color::-webkit-color-swatch {
            border: 0 !important;
            border-radius: var(--bs-border-radius)
        }

        .form-control-color.form-control-sm {
            height: calc(1.5em + .5rem + calc(var(--bs-border-width) * 2))
        }

        .form-control-color.form-control-lg {
            height: calc(1.5em + 1rem + calc(var(--bs-border-width) * 2))
        }

        .form-select {
            --bs-form-select-bg-img: url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 16 16'%3e%3cpath fill='none' stroke='%23343a40' stroke-linecap='round' stroke-linejoin='round' stroke-width='2' d='m2 5 6 6 6-6'/%3e%3c/svg%3e");
            display: block;
            width: 100%;
            padding: .375rem 2.25rem .375rem .75rem;
            font-size: 1rem;
            font-weight: 400;
            line-height: 1.5;
            color: var(--bs-body-color);
            background-color: var(--bs-body-bg);
            background-image: var(--bs-form-select-bg-img), var(--bs-form-select-bg-icon, none);
            background-repeat: no-repeat;
            background-position: right .75rem center;
            background-size: 16px 12px;
            border: var(--bs-border-width) solid var(--bs-border-color);
            border-radius: var(--bs-border-radius);
            transition: border-color .15s ease-in-out, box-shadow .15s ease-in-out;
            -webkit-appearance: none;
            -moz-appearance: none;
            appearance: none
        }

        @media (prefers-reduced-motion:reduce) {
            .form-select {
                transition: none
            }
        }

        .form-select:focus {
            border-color: #86b7fe;
            outline: 0;
            box-shadow: 0 0 0 .25rem rgba(13, 110, 253, .25)
        }

        .form-select[multiple],
        .form-select[size]:not([size="1"]) {
            padding-right: .75rem;
            background-image: none
        }

        .form-select:disabled {
            background-color: var(--bs-secondary-bg)
        }

        .form-select:-moz-focusring {
            color: transparent;
            text-shadow: 0 0 0 var(--bs-body-color)
        }

        .form-select-sm {
            padding-top: .25rem;
            padding-bottom: .25rem;
            padding-left: .5rem;
            font-size: .875rem;
            border-radius: var(--bs-border-radius-sm)
        }

        .form-select-lg {
            padding-top: .5rem;
            padding-bottom: .5rem;
            padding-left: 1rem;
            font-size: 1.25rem;
            border-radius: var(--bs-border-radius-lg)
        }

        [data-bs-theme=dark] .form-select {
            --bs-form-select-bg-img: url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 16 16'%3e%3cpath fill='none' stroke='%23adb5bd' stroke-linecap='round' stroke-linejoin='round' stroke-width='2' d='m2 5 6 6 6-6'/%3e%3c/svg%3e")
        }

        .form-check {
            display: block;
            min-height: 1.5rem;
            padding-left: 1.5em;
            margin-bottom: .125rem
        }

        .form-check .form-check-input {
            float: left;
            margin-left: -1.5em
        }

        .form-check-reverse {
            padding-right: 1.5em;
            padding-left: 0;
            text-align: right
        }

        .form-check-reverse .form-check-input {
            float: right;
            margin-right: -1.5em;
            margin-left: 0
        }

        .form-check-input {
            --bs-form-check-bg: var(--bs-body-bg);
            width: 1em;
            height: 1em;
            margin-top: .25em;
            vertical-align: top;
            background-color: var(--bs-form-check-bg);
            background-image: var(--bs-form-check-bg-image);
            background-repeat: no-repeat;
            background-position: center;
            background-size: contain;
            border: var(--bs-border-width) solid var(--bs-border-color);
            -webkit-appearance: none;
            -moz-appearance: none;
            appearance: none;
            -webkit-print-color-adjust: exact;
            color-adjust: exact;
            print-color-adjust: exact
        }

        .form-check-input[type=checkbox] {
            border-radius: .25em
        }

        .form-check-input[type=radio] {
            border-radius: 50%
        }

        .form-check-input:active {
            filter: brightness(90%)
        }

        .form-check-input:focus {
            border-color: #86b7fe;
            outline: 0;
            box-shadow: 0 0 0 .25rem rgba(13, 110, 253, .25)
        }

        .form-check-input:checked {
            background-color: #0d6efd;
            border-color: #0d6efd
        }

        .form-check-input:checked[type=checkbox] {
            --bs-form-check-bg-image: url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 20 20'%3e%3cpath fill='none' stroke='%23fff' stroke-linecap='round' stroke-linejoin='round' stroke-width='3' d='m6 10 3 3 6-6'/%3e%3c/svg%3e")
        }

        .form-check-input:checked[type=radio] {
            --bs-form-check-bg-image: url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' viewBox='-4 -4 8 8'%3e%3ccircle r='2' fill='%23fff'/%3e%3c/svg%3e")
        }

        .form-check-input[type=checkbox]:indeterminate {
            background-color: #0d6efd;
            border-color: #0d6efd;
            --bs-form-check-bg-image: url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 20 20'%3e%3cpath fill='none' stroke='%23fff' stroke-linecap='round' stroke-linejoin='round' stroke-width='3' d='M6 10h8'/%3e%3c/svg%3e")
        }

        .form-check-input:disabled {
            pointer-events: none;
            filter: none;
            opacity: .5
        }

        .form-check-input:disabled~.form-check-label,
        .form-check-input[disabled]~.form-check-label {
            cursor: default;
            opacity: .5
        }

        .form-switch {
            padding-left: 2.5em
        }

        .form-switch .form-check-input {
            --bs-form-switch-bg: url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' viewBox='-4 -4 8 8'%3e%3ccircle r='3' fill='rgba%280, 0, 0, 0.25%29'/%3e%3c/svg%3e");
            width: 2em;
            margin-left: -2.5em;
            background-image: var(--bs-form-switch-bg);
            background-position: left center;
            border-radius: 2em;
            transition: background-position .15s ease-in-out
        }

        @media (prefers-reduced-motion:reduce) {
            .form-switch .form-check-input {
                transition: none
            }
        }

        .form-switch .form-check-input:focus {
            --bs-form-switch-bg: url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' viewBox='-4 -4 8 8'%3e%3ccircle r='3' fill='%2386b7fe'/%3e%3c/svg%3e")
        }

        .form-switch .form-check-input:checked {
            background-position: right center;
            --bs-form-switch-bg: url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' viewBox='-4 -4 8 8'%3e%3ccircle r='3' fill='%23fff'/%3e%3c/svg%3e")
        }

        .form-switch.form-check-reverse {
            padding-right: 2.5em;
            padding-left: 0
        }

        .form-switch.form-check-reverse .form-check-input {
            margin-right: -2.5em;
            margin-left: 0
        }

        .form-check-inline {
            display: inline-block;
            margin-right: 1rem
        }

        .btn-check {
            position: absolute;
            clip: rect(0, 0, 0, 0);
            pointer-events: none
        }

        .btn-check:disabled+.btn,
        .btn-check[disabled]+.btn {
            pointer-events: none;
            filter: none;
            opacity: .65
        }

        [data-bs-theme=dark] .form-switch .form-check-input:not(:checked):not(:focus) {
            --bs-form-switch-bg: url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' viewBox='-4 -4 8 8'%3e%3ccircle r='3' fill='rgba%28255, 255, 255, 0.25%29'/%3e%3c/svg%3e")
        }

        .form-range {
            width: 100%;
            height: 1.5rem;
            padding: 0;
            background-color: transparent;
            -webkit-appearance: none;
            -moz-appearance: none;
            appearance: none
        }

        .form-range:focus {
            outline: 0
        }

        .form-range:focus::-webkit-slider-thumb {
            box-shadow: 0 0 0 1px #fff, 0 0 0 .25rem rgba(13, 110, 253, .25)
        }

        .form-range:focus::-moz-range-thumb {
            box-shadow: 0 0 0 1px #fff, 0 0 0 .25rem rgba(13, 110, 253, .25)
        }

        .form-range::-moz-focus-outer {
            border: 0
        }

        .form-range::-webkit-slider-thumb {
            width: 1rem;
            height: 1rem;
            margin-top: -.25rem;
            background-color: #0d6efd;
            border: 0;
            border-radius: 1rem;
            -webkit-transition: background-color .15s ease-in-out, border-color .15s ease-in-out, box-shadow .15s ease-in-out;
            transition: background-color .15s ease-in-out, border-color .15s ease-in-out, box-shadow .15s ease-in-out;
            -webkit-appearance: none;
            appearance: none
        }

        @media (prefers-reduced-motion:reduce) {
            .form-range::-webkit-slider-thumb {
                -webkit-transition: none;
                transition: none
            }
        }

        .form-range::-webkit-slider-thumb:active {
            background-color: #b6d4fe
        }

        .form-range::-webkit-slider-runnable-track {
            width: 100%;
            height: .5rem;
            color: transparent;
            cursor: pointer;
            background-color: var(--bs-tertiary-bg);
            border-color: transparent;
            border-radius: 1rem
        }

        .form-range::-moz-range-thumb {
            width: 1rem;
            height: 1rem;
            background-color: #0d6efd;
            border: 0;
            border-radius: 1rem;
            -moz-transition: background-color .15s ease-in-out, border-color .15s ease-in-out, box-shadow .15s ease-in-out;
            transition: background-color .15s ease-in-out, border-color .15s ease-in-out, box-shadow .15s ease-in-out;
            -moz-appearance: none;
            appearance: none
        }

        @media (prefers-reduced-motion:reduce) {
            .form-range::-moz-range-thumb {
                -moz-transition: none;
                transition: none
            }
        }

        .form-range::-moz-range-thumb:active {
            background-color: #b6d4fe
        }

        .form-range::-moz-range-track {
            width: 100%;
            height: .5rem;
            color: transparent;
            cursor: pointer;
            background-color: var(--bs-tertiary-bg);
            border-color: transparent;
            border-radius: 1rem
        }

        .form-range:disabled {
            pointer-events: none
        }

        .form-range:disabled::-webkit-slider-thumb {
            background-color: var(--bs-secondary-color)
        }

        .form-range:disabled::-moz-range-thumb {
            background-color: var(--bs-secondary-color)
        }

        .form-floating {
            position: relative
        }

        .form-floating>.form-control,
        .form-floating>.form-control-plaintext,
        .form-floating>.form-select {
            height: calc(3.5rem + calc(var(--bs-border-width) * 2));
            min-height: calc(3.5rem + calc(var(--bs-border-width) * 2));
            line-height: 1.25
        }

        .form-floating>label {
            position: absolute;
            top: 0;
            left: 0;
            z-index: 2;
            height: 100%;
            padding: 1rem .75rem;
            overflow: hidden;
            text-align: start;
            text-overflow: ellipsis;
            white-space: nowrap;
            pointer-events: none;
            border: var(--bs-border-width) solid transparent;
            transform-origin: 0 0;
            transition: opacity .1s ease-in-out, transform .1s ease-in-out
        }

        @media (prefers-reduced-motion:reduce) {
            .form-floating>label {
                transition: none
            }
        }

        .form-floating>.form-control,
        .form-floating>.form-control-plaintext {
            padding: 1rem .75rem
        }

        .form-floating>.form-control-plaintext::-moz-placeholder,
        .form-floating>.form-control::-moz-placeholder {
            color: transparent
        }

        .form-floating>.form-control-plaintext::placeholder,
        .form-floating>.form-control::placeholder {
            color: transparent
        }

        .form-floating>.form-control-plaintext:not(:-moz-placeholder-shown),
        .form-floating>.form-control:not(:-moz-placeholder-shown) {
            padding-top: 1.625rem;
            padding-bottom: .625rem
        }

        .form-floating>.form-control-plaintext:focus,
        .form-floating>.form-control-plaintext:not(:placeholder-shown),
        .form-floating>.form-control:focus,
        .form-floating>.form-control:not(:placeholder-shown) {
            padding-top: 1.625rem;
            padding-bottom: .625rem
        }

        .form-floating>.form-control-plaintext:-webkit-autofill,
        .form-floating>.form-control:-webkit-autofill {
            padding-top: 1.625rem;
            padding-bottom: .625rem
        }

        .form-floating>.form-select {
            padding-top: 1.625rem;
            padding-bottom: .625rem
        }

        .form-floating>.form-control:not(:-moz-placeholder-shown)~label {
            color: rgba(var(--bs-body-color-rgb), .65);
            transform: scale(.85) translateY(-.5rem) translateX(.15rem)
        }

        .form-floating>.form-control-plaintext~label,
        .form-floating>.form-control:focus~label,
        .form-floating>.form-control:not(:placeholder-shown)~label,
        .form-floating>.form-select~label {
            color: rgba(var(--bs-body-color-rgb), .65);
            transform: scale(.85) translateY(-.5rem) translateX(.15rem)
        }

        .form-floating>.form-control:not(:-moz-placeholder-shown)~label::after {
            position: absolute;
            inset: 1rem 0.375rem;
            z-index: -1;
            height: 1.5em;
            content: "";
            background-color: var(--bs-body-bg);
            border-radius: var(--bs-border-radius)
        }

        .form-floating>.form-control-plaintext~label::after,
        .form-floating>.form-control:focus~label::after,
        .form-floating>.form-control:not(:placeholder-shown)~label::after,
        .form-floating>.form-select~label::after {
            position: absolute;
            inset: 1rem 0.375rem;
            z-index: -1;
            height: 1.5em;
            content: "";
            background-color: var(--bs-body-bg);
            border-radius: var(--bs-border-radius)
        }

        .form-floating>.form-control:-webkit-autofill~label {
            color: rgba(var(--bs-body-color-rgb), .65);
            transform: scale(.85) translateY(-.5rem) translateX(.15rem)
        }

        .form-floating>.form-control-plaintext~label {
            border-width: var(--bs-border-width) 0
        }

        .form-floating>:disabled~label {
            color: #6c757d
        }

        .form-floating>:disabled~label::after {
            background-color: var(--bs-secondary-bg)
        }

        .input-group {
            position: relative;
            display: flex;
            flex-wrap: wrap;
            align-items: stretch;
            width: 100%
        }

        .input-group>.form-control,
        .input-group>.form-floating,
        .input-group>.form-select {
            position: relative;
            flex: 1 1 auto;
            width: 1%;
            min-width: 0
        }

        .input-group>.form-control:focus,
        .input-group>.form-floating:focus-within,
        .input-group>.form-select:focus {
            z-index: 5
        }

        .input-group .btn {
            position: relative;
            z-index: 2
        }

        .input-group .btn:focus {
            z-index: 5
        }

        .input-group-text {
            display: flex;
            align-items: center;
            padding: .375rem .75rem;
            font-size: 1rem;
            font-weight: 400;
            line-height: 1.5;
            color: var(--bs-body-color);
            text-align: center;
            white-space: nowrap;
            background-color: var(--bs-tertiary-bg);
            border: var(--bs-border-width) solid var(--bs-border-color);
            border-radius: var(--bs-border-radius)
        }

        .input-group-lg>.btn,
        .input-group-lg>.form-control,
        .input-group-lg>.form-select,
        .input-group-lg>.input-group-text {
            padding: .5rem 1rem;
            font-size: 1.25rem;
            border-radius: var(--bs-border-radius-lg)
        }

        .input-group-sm>.btn,
        .input-group-sm>.form-control,
        .input-group-sm>.form-select,
        .input-group-sm>.input-group-text {
            padding: .25rem .5rem;
            font-size: .875rem;
            border-radius: var(--bs-border-radius-sm)
        }

        .input-group-lg>.form-select,
        .input-group-sm>.form-select {
            padding-right: 3rem
        }

        .input-group:not(.has-validation)>.dropdown-toggle:nth-last-child(n+3),
        .input-group:not(.has-validation)>.form-floating:not(:last-child)>.form-control,
        .input-group:not(.has-validation)>.form-floating:not(:last-child)>.form-select,
        .input-group:not(.has-validation)>:not(:last-child):not(.dropdown-toggle):not(.dropdown-menu):not(.form-floating) {
            border-top-right-radius: 0;
            border-bottom-right-radius: 0
        }

        .input-group.has-validation>.dropdown-toggle:nth-last-child(n+4),
        .input-group.has-validation>.form-floating:nth-last-child(n+3)>.form-control,
        .input-group.has-validation>.form-floating:nth-last-child(n+3)>.form-select,
        .input-group.has-validation>:nth-last-child(n+3):not(.dropdown-toggle):not(.dropdown-menu):not(.form-floating) {
            border-top-right-radius: 0;
            border-bottom-right-radius: 0
        }

        .input-group>:not(:first-child):not(.dropdown-menu):not(.valid-tooltip):not(.valid-feedback):not(.invalid-tooltip):not(.invalid-feedback) {
            margin-left: calc(var(--bs-border-width) * -1);
            border-top-left-radius: 0;
            border-bottom-left-radius: 0
        }

        .input-group>.form-floating:not(:first-child)>.form-control,
        .input-group>.form-floating:not(:first-child)>.form-select {
            border-top-left-radius: 0;
            border-bottom-left-radius: 0
        }

        .valid-feedback {
            display: none;
            width: 100%;
            margin-top: .25rem;
            font-size: .875em;
            color: var(--bs-form-valid-color)
        }

        .valid-tooltip {
            position: absolute;
            top: 100%;
            z-index: 5;
            display: none;
            max-width: 100%;
            padding: .25rem .5rem;
            margin-top: .1rem;
            font-size: .875rem;
            color: #fff;
            background-color: var(--bs-success);
            border-radius: var(--bs-border-radius)
        }

        .is-valid~.valid-feedback,
        .is-valid~.valid-tooltip,
        .was-validated :valid~.valid-feedback,
        .was-validated :valid~.valid-tooltip {
            display: block
        }

        .form-control.is-valid,
        .was-validated .form-control:valid {
            border-color: var(--bs-form-valid-border-color);
            padding-right: calc(1.5em + .75rem);
            background-image: url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 8 8'%3e%3cpath fill='%23198754' d='M2.3 6.73.6 4.53c-.4-1.04.46-1.4 1.1-.8l1.1 1.4 3.4-3.8c.6-.63 1.6-.27 1.2.7l-4 4.6c-.43.5-.8.4-1.1.1z'/%3e%3c/svg%3e");
            background-repeat: no-repeat;
            background-position: right calc(.375em + .1875rem) center;
            background-size: calc(.75em + .375rem) calc(.75em + .375rem)
        }

        .form-control.is-valid:focus,
        .was-validated .form-control:valid:focus {
            border-color: var(--bs-form-valid-border-color);
            box-shadow: 0 0 0 .25rem rgba(var(--bs-success-rgb), .25)
        }

        .was-validated textarea.form-control:valid,
        textarea.form-control.is-valid {
            padding-right: calc(1.5em + .75rem);
            background-position: top calc(.375em + .1875rem) right calc(.375em + .1875rem)
        }

        .form-select.is-valid,
        .was-validated .form-select:valid {
            border-color: var(--bs-form-valid-border-color)
        }

        .form-select.is-valid:not([multiple]):not([size]),
        .form-select.is-valid:not([multiple])[size="1"],
        .was-validated .form-select:valid:not([multiple]):not([size]),
        .was-validated .form-select:valid:not([multiple])[size="1"] {
            --bs-form-select-bg-icon: url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 8 8'%3e%3cpath fill='%23198754' d='M2.3 6.73.6 4.53c-.4-1.04.46-1.4 1.1-.8l1.1 1.4 3.4-3.8c.6-.63 1.6-.27 1.2.7l-4 4.6c-.43.5-.8.4-1.1.1z'/%3e%3c/svg%3e");
            padding-right: 4.125rem;
            background-position: right .75rem center, center right 2.25rem;
            background-size: 16px 12px, calc(.75em + .375rem) calc(.75em + .375rem)
        }

        .form-select.is-valid:focus,
        .was-validated .form-select:valid:focus {
            border-color: var(--bs-form-valid-border-color);
            box-shadow: 0 0 0 .25rem rgba(var(--bs-success-rgb), .25)
        }

        .form-control-color.is-valid,
        .was-validated .form-control-color:valid {
            width: calc(3rem + calc(1.5em + .75rem))
        }

        .form-check-input.is-valid,
        .was-validated .form-check-input:valid {
            border-color: var(--bs-form-valid-border-color)
        }

        .form-check-input.is-valid:checked,
        .was-validated .form-check-input:valid:checked {
            background-color: var(--bs-form-valid-color)
        }

        .form-check-input.is-valid:focus,
        .was-validated .form-check-input:valid:focus {
            box-shadow: 0 0 0 .25rem rgba(var(--bs-success-rgb), .25)
        }

        .form-check-input.is-valid~.form-check-label,
        .was-validated .form-check-input:valid~.form-check-label {
            color: var(--bs-form-valid-color)
        }

        .form-check-inline .form-check-input~.valid-feedback {
            margin-left: .5em
        }

        .input-group>.form-control:not(:focus).is-valid,
        .input-group>.form-floating:not(:focus-within).is-valid,
        .input-group>.form-select:not(:focus).is-valid,
        .was-validated .input-group>.form-control:not(:focus):valid,
        .was-validated .input-group>.form-floating:not(:focus-within):valid,
        .was-validated .input-group>.form-select:not(:focus):valid {
            z-index: 3
        }

        .invalid-feedback {
            display: none;
            width: 100%;
            margin-top: .25rem;
            font-size: .875em;
            color: var(--bs-form-invalid-color)
        }

        .invalid-tooltip {
            position: absolute;
            top: 100%;
            z-index: 5;
            display: none;
            max-width: 100%;
            padding: .25rem .5rem;
            margin-top: .1rem;
            font-size: .875rem;
            color: #fff;
            background-color: var(--bs-danger);
            border-radius: var(--bs-border-radius)
        }

        .is-invalid~.invalid-feedback,
        .is-invalid~.invalid-tooltip,
        .was-validated :invalid~.invalid-feedback,
        .was-validated :invalid~.invalid-tooltip {
            display: block
        }

        .form-control.is-invalid,
        .was-validated .form-control:invalid {
            border-color: var(--bs-form-invalid-border-color);
            padding-right: calc(1.5em + .75rem);
            background-image: url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 12 12' width='12' height='12' fill='none' stroke='%23dc3545'%3e%3ccircle cx='6' cy='6' r='4.5'/%3e%3cpath stroke-linejoin='round' d='M5.8 3.6h.4L6 6.5z'/%3e%3ccircle cx='6' cy='8.2' r='.6' fill='%23dc3545' stroke='none'/%3e%3c/svg%3e");
            background-repeat: no-repeat;
            background-position: right calc(.375em + .1875rem) center;
            background-size: calc(.75em + .375rem) calc(.75em + .375rem)
        }

        .form-control.is-invalid:focus,
        .was-validated .form-control:invalid:focus {
            border-color: var(--bs-form-invalid-border-color);
            box-shadow: 0 0 0 .25rem rgba(var(--bs-danger-rgb), .25)
        }

        .was-validated textarea.form-control:invalid,
        textarea.form-control.is-invalid {
            padding-right: calc(1.5em + .75rem);
            background-position: top calc(.375em + .1875rem) right calc(.375em + .1875rem)
        }

        .form-select.is-invalid,
        .was-validated .form-select:invalid {
            border-color: var(--bs-form-invalid-border-color)
        }

        .form-select.is-invalid:not([multiple]):not([size]),
        .form-select.is-invalid:not([multiple])[size="1"],
        .was-validated .form-select:invalid:not([multiple]):not([size]),
        .was-validated .form-select:invalid:not([multiple])[size="1"] {
            --bs-form-select-bg-icon: url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 12 12' width='12' height='12' fill='none' stroke='%23dc3545'%3e%3ccircle cx='6' cy='6' r='4.5'/%3e%3cpath stroke-linejoin='round' d='M5.8 3.6h.4L6 6.5z'/%3e%3ccircle cx='6' cy='8.2' r='.6' fill='%23dc3545' stroke='none'/%3e%3c/svg%3e");
            padding-right: 4.125rem;
            background-position: right .75rem center, center right 2.25rem;
            background-size: 16px 12px, calc(.75em + .375rem) calc(.75em + .375rem)
        }

        .form-select.is-invalid:focus,
        .was-validated .form-select:invalid:focus {
            border-color: var(--bs-form-invalid-border-color);
            box-shadow: 0 0 0 .25rem rgba(var(--bs-danger-rgb), .25)
        }

        .form-control-color.is-invalid,
        .was-validated .form-control-color:invalid {
            width: calc(3rem + calc(1.5em + .75rem))
        }

        .form-check-input.is-invalid,
        .was-validated .form-check-input:invalid {
            border-color: var(--bs-form-invalid-border-color)
        }

        .form-check-input.is-invalid:checked,
        .was-validated .form-check-input:invalid:checked {
            background-color: var(--bs-form-invalid-color)
        }

        .form-check-input.is-invalid:focus,
        .was-validated .form-check-input:invalid:focus {
            box-shadow: 0 0 0 .25rem rgba(var(--bs-danger-rgb), .25)
        }

        .form-check-input.is-invalid~.form-check-label,
        .was-validated .form-check-input:invalid~.form-check-label {
            color: var(--bs-form-invalid-color)
        }

        .form-check-inline .form-check-input~.invalid-feedback {
            margin-left: .5em
        }

        .input-group>.form-control:not(:focus).is-invalid,
        .input-group>.form-floating:not(:focus-within).is-invalid,
        .input-group>.form-select:not(:focus).is-invalid,
        .was-validated .input-group>.form-control:not(:focus):invalid,
        .was-validated .input-group>.form-floating:not(:focus-within):invalid,
        .was-validated .input-group>.form-select:not(:focus):invalid {
            z-index: 4
        }

        .btn {
            --bs-btn-padding-x: 0.75rem;
            --bs-btn-padding-y: 0.375rem;
            --bs-btn-font-family: ;
            --bs-btn-font-size: 1rem;
            --bs-btn-font-weight: 400;
            --bs-btn-line-height: 1.5;
            --bs-btn-color: var(--bs-body-color);
            --bs-btn-bg: transparent;
            --bs-btn-border-width: var(--bs-border-width);
            --bs-btn-border-color: transparent;
            --bs-btn-border-radius: var(--bs-border-radius);
            --bs-btn-hover-border-color: transparent;
            --bs-btn-box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.15), 0 1px 1px rgba(0, 0, 0, 0.075);
            --bs-btn-disabled-opacity: 0.65;
            --bs-btn-focus-box-shadow: 0 0 0 0.25rem rgba(var(--bs-btn-focus-shadow-rgb), .5);
            display: inline-block;
            padding: var(--bs-btn-padding-y) var(--bs-btn-padding-x);
            font-family: var(--bs-btn-font-family);
            font-size: var(--bs-btn-font-size);
            font-weight: var(--bs-btn-font-weight);
            line-height: var(--bs-btn-line-height);
            color: var(--bs-btn-color);
            text-align: center;
            text-decoration: none;
            vertical-align: middle;
            cursor: pointer;
            -webkit-user-select: none;
            -moz-user-select: none;
            user-select: none;
            border: var(--bs-btn-border-width) solid var(--bs-btn-border-color);
            border-radius: var(--bs-btn-border-radius);
            background-color: var(--bs-btn-bg);
            transition: color .15s ease-in-out, background-color .15s ease-in-out, border-color .15s ease-in-out, box-shadow .15s ease-in-out
        }

        @media (prefers-reduced-motion:reduce) {
            .btn {
                transition: none
            }
        }

        .btn:hover {
            color: var(--bs-btn-hover-color);
            background-color: var(--bs-btn-hover-bg);
            border-color: var(--bs-btn-hover-border-color)
        }

        .btn-check+.btn:hover {
            color: var(--bs-btn-color);
            background-color: var(--bs-btn-bg);
            border-color: var(--bs-btn-border-color)
        }

        .btn:focus-visible {
            color: var(--bs-btn-hover-color);
            background-color: var(--bs-btn-hover-bg);
            border-color: var(--bs-btn-hover-border-color);
            outline: 0;
            box-shadow: var(--bs-btn-focus-box-shadow)
        }

        .btn-check:focus-visible+.btn {
            border-color: var(--bs-btn-hover-border-color);
            outline: 0;
            box-shadow: var(--bs-btn-focus-box-shadow)
        }

        .btn-check:checked+.btn,
        .btn.active,
        .btn.show,
        .btn:first-child:active,
        :not(.btn-check)+.btn:active {
            color: var(--bs-btn-active-color);
            background-color: var(--bs-btn-active-bg);
            border-color: var(--bs-btn-active-border-color)
        }

        .btn-check:checked+.btn:focus-visible,
        .btn.active:focus-visible,
        .btn.show:focus-visible,
        .btn:first-child:active:focus-visible,
        :not(.btn-check)+.btn:active:focus-visible {
            box-shadow: var(--bs-btn-focus-box-shadow)
        }

        .btn.disabled,
        .btn:disabled,
        fieldset:disabled .btn {
            color: var(--bs-btn-disabled-color);
            pointer-events: none;
            background-color: var(--bs-btn-disabled-bg);
            border-color: var(--bs-btn-disabled-border-color);
            opacity: var(--bs-btn-disabled-opacity)
        }

        .btn-primary {
            --bs-btn-color: #fff;
            --bs-btn-bg: #0d6efd;
            --bs-btn-border-color: #0d6efd;
            --bs-btn-hover-color: #fff;
            --bs-btn-hover-bg: #0b5ed7;
            --bs-btn-hover-border-color: #0a58ca;
            --bs-btn-focus-shadow-rgb: 49, 132, 253;
            --bs-btn-active-color: #fff;
            --bs-btn-active-bg: #0a58ca;
            --bs-btn-active-border-color: #0a53be;
            --bs-btn-active-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
            --bs-btn-disabled-color: #fff;
            --bs-btn-disabled-bg: #0d6efd;
            --bs-btn-disabled-border-color: #0d6efd
        }

        .btn-secondary {
            --bs-btn-color: #fff;
            --bs-btn-bg: #6c757d;
            --bs-btn-border-color: #6c757d;
            --bs-btn-hover-color: #fff;
            --bs-btn-hover-bg: #5c636a;
            --bs-btn-hover-border-color: #565e64;
            --bs-btn-focus-shadow-rgb: 130, 138, 145;
            --bs-btn-active-color: #fff;
            --bs-btn-active-bg: #565e64;
            --bs-btn-active-border-color: #51585e;
            --bs-btn-active-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
            --bs-btn-disabled-color: #fff;
            --bs-btn-disabled-bg: #6c757d;
            --bs-btn-disabled-border-color: #6c757d
        }

        .btn-success {
            --bs-btn-color: #fff;
            --bs-btn-bg: #198754;
            --bs-btn-border-color: #198754;
            --bs-btn-hover-color: #fff;
            --bs-btn-hover-bg: #157347;
            --bs-btn-hover-border-color: #146c43;
            --bs-btn-focus-shadow-rgb: 60, 153, 110;
            --bs-btn-active-color: #fff;
            --bs-btn-active-bg: #146c43;
            --bs-btn-active-border-color: #13653f;
            --bs-btn-active-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
            --bs-btn-disabled-color: #fff;
            --bs-btn-disabled-bg: #198754;
            --bs-btn-disabled-border-color: #198754
        }

        .btn-info {
            --bs-btn-color: #000;
            --bs-btn-bg: #0dcaf0;
            --bs-btn-border-color: #0dcaf0;
            --bs-btn-hover-color: #000;
            --bs-btn-hover-bg: #31d2f2;
            --bs-btn-hover-border-color: #25cff2;
            --bs-btn-focus-shadow-rgb: 11, 172, 204;
            --bs-btn-active-color: #000;
            --bs-btn-active-bg: #3dd5f3;
            --bs-btn-active-border-color: #25cff2;
            --bs-btn-active-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
            --bs-btn-disabled-color: #000;
            --bs-btn-disabled-bg: #0dcaf0;
            --bs-btn-disabled-border-color: #0dcaf0
        }

        .btn-warning {
            --bs-btn-color: #000;
            --bs-btn-bg: #ffc107;
            --bs-btn-border-color: #ffc107;
            --bs-btn-hover-color: #000;
            --bs-btn-hover-bg: #ffca2c;
            --bs-btn-hover-border-color: #ffc720;
            --bs-btn-focus-shadow-rgb: 217, 164, 6;
            --bs-btn-active-color: #000;
            --bs-btn-active-bg: #ffcd39;
            --bs-btn-active-border-color: #ffc720;
            --bs-btn-active-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
            --bs-btn-disabled-color: #000;
            --bs-btn-disabled-bg: #ffc107;
            --bs-btn-disabled-border-color: #ffc107
        }

        .btn-danger {
            --bs-btn-color: #fff;
            --bs-btn-bg: #dc3545;
            --bs-btn-border-color: #dc3545;
            --bs-btn-hover-color: #fff;
            --bs-btn-hover-bg: #bb2d3b;
            --bs-btn-hover-border-color: #b02a37;
            --bs-btn-focus-shadow-rgb: 225, 83, 97;
            --bs-btn-active-color: #fff;
            --bs-btn-active-bg: #b02a37;
            --bs-btn-active-border-color: #a52834;
            --bs-btn-active-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
            --bs-btn-disabled-color: #fff;
            --bs-btn-disabled-bg: #dc3545;
            --bs-btn-disabled-border-color: #dc3545
        }

        .btn-light {
            --bs-btn-color: #000;
            --bs-btn-bg: #f8f9fa;
            --bs-btn-border-color: #f8f9fa;
            --bs-btn-hover-color: #000;
            --bs-btn-hover-bg: #d3d4d5;
            --bs-btn-hover-border-color: #c6c7c8;
            --bs-btn-focus-shadow-rgb: 211, 212, 213;
            --bs-btn-active-color: #000;
            --bs-btn-active-bg: #c6c7c8;
            --bs-btn-active-border-color: #babbbc;
            --bs-btn-active-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
            --bs-btn-disabled-color: #000;
            --bs-btn-disabled-bg: #f8f9fa;
            --bs-btn-disabled-border-color: #f8f9fa
        }

        .btn-dark {
            --bs-btn-color: #fff;
            --bs-btn-bg: #212529;
            --bs-btn-border-color: #212529;
            --bs-btn-hover-color: #fff;
            --bs-btn-hover-bg: #424649;
            --bs-btn-hover-border-color: #373b3e;
            --bs-btn-focus-shadow-rgb: 66, 70, 73;
            --bs-btn-active-color: #fff;
            --bs-btn-active-bg: #4d5154;
            --bs-btn-active-border-color: #373b3e;
            --bs-btn-active-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
            --bs-btn-disabled-color: #fff;
            --bs-btn-disabled-bg: #212529;
            --bs-btn-disabled-border-color: #212529
        }

        .btn-outline-primary {
            --bs-btn-color: #0d6efd;
            --bs-btn-border-color: #0d6efd;
            --bs-btn-hover-color: #fff;
            --bs-btn-hover-bg: #0d6efd;
            --bs-btn-hover-border-color: #0d6efd;
            --bs-btn-focus-shadow-rgb: 13, 110, 253;
            --bs-btn-active-color: #fff;
            --bs-btn-active-bg: #0d6efd;
            --bs-btn-active-border-color: #0d6efd;
            --bs-btn-active-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
            --bs-btn-disabled-color: #0d6efd;
            --bs-btn-disabled-bg: transparent;
            --bs-btn-disabled-border-color: #0d6efd;
            --bs-gradient: none
        }

        .btn-outline-secondary {
            --bs-btn-color: #6c757d;
            --bs-btn-border-color: #6c757d;
            --bs-btn-hover-color: #fff;
            --bs-btn-hover-bg: #6c757d;
            --bs-btn-hover-border-color: #6c757d;
            --bs-btn-focus-shadow-rgb: 108, 117, 125;
            --bs-btn-active-color: #fff;
            --bs-btn-active-bg: #6c757d;
            --bs-btn-active-border-color: #6c757d;
            --bs-btn-active-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
            --bs-btn-disabled-color: #6c757d;
            --bs-btn-disabled-bg: transparent;
            --bs-btn-disabled-border-color: #6c757d;
            --bs-gradient: none
        }

        .btn-outline-success {
            --bs-btn-color: #198754;
            --bs-btn-border-color: #198754;
            --bs-btn-hover-color: #fff;
            --bs-btn-hover-bg: #198754;
            --bs-btn-hover-border-color: #198754;
            --bs-btn-focus-shadow-rgb: 25, 135, 84;
            --bs-btn-active-color: #fff;
            --bs-btn-active-bg: #198754;
            --bs-btn-active-border-color: #198754;
            --bs-btn-active-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
            --bs-btn-disabled-color: #198754;
            --bs-btn-disabled-bg: transparent;
            --bs-btn-disabled-border-color: #198754;
            --bs-gradient: none
        }

        .btn-outline-info {
            --bs-btn-color: #0dcaf0;
            --bs-btn-border-color: #0dcaf0;
            --bs-btn-hover-color: #000;
            --bs-btn-hover-bg: #0dcaf0;
            --bs-btn-hover-border-color: #0dcaf0;
            --bs-btn-focus-shadow-rgb: 13, 202, 240;
            --bs-btn-active-color: #000;
            --bs-btn-active-bg: #0dcaf0;
            --bs-btn-active-border-color: #0dcaf0;
            --bs-btn-active-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
            --bs-btn-disabled-color: #0dcaf0;
            --bs-btn-disabled-bg: transparent;
            --bs-btn-disabled-border-color: #0dcaf0;
            --bs-gradient: none
        }

        .btn-outline-warning {
            --bs-btn-color: #ffc107;
            --bs-btn-border-color: #ffc107;
            --bs-btn-hover-color: #000;
            --bs-btn-hover-bg: #ffc107;
            --bs-btn-hover-border-color: #ffc107;
            --bs-btn-focus-shadow-rgb: 255, 193, 7;
            --bs-btn-active-color: #000;
            --bs-btn-active-bg: #ffc107;
            --bs-btn-active-border-color: #ffc107;
            --bs-btn-active-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
            --bs-btn-disabled-color: #ffc107;
            --bs-btn-disabled-bg: transparent;
            --bs-btn-disabled-border-color: #ffc107;
            --bs-gradient: none
        }

        .btn-outline-danger {
            --bs-btn-color: #dc3545;
            --bs-btn-border-color: #dc3545;
            --bs-btn-hover-color: #fff;
            --bs-btn-hover-bg: #dc3545;
            --bs-btn-hover-border-color: #dc3545;
            --bs-btn-focus-shadow-rgb: 220, 53, 69;
            --bs-btn-active-color: #fff;
            --bs-btn-active-bg: #dc3545;
            --bs-btn-active-border-color: #dc3545;
            --bs-btn-active-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
            --bs-btn-disabled-color: #dc3545;
            --bs-btn-disabled-bg: transparent;
            --bs-btn-disabled-border-color: #dc3545;
            --bs-gradient: none
        }

        .btn-outline-light {
            --bs-btn-color: #f8f9fa;
            --bs-btn-border-color: #f8f9fa;
            --bs-btn-hover-color: #000;
            --bs-btn-hover-bg: #f8f9fa;
            --bs-btn-hover-border-color: #f8f9fa;
            --bs-btn-focus-shadow-rgb: 248, 249, 250;
            --bs-btn-active-color: #000;
            --bs-btn-active-bg: #f8f9fa;
            --bs-btn-active-border-color: #f8f9fa;
            --bs-btn-active-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
            --bs-btn-disabled-color: #f8f9fa;
            --bs-btn-disabled-bg: transparent;
            --bs-btn-disabled-border-color: #f8f9fa;
            --bs-gradient: none
        }

        .btn-outline-dark {
            --bs-btn-color: #212529;
            --bs-btn-border-color: #212529;
            --bs-btn-hover-color: #fff;
            --bs-btn-hover-bg: #212529;
            --bs-btn-hover-border-color: #212529;
            --bs-btn-focus-shadow-rgb: 33, 37, 41;
            --bs-btn-active-color: #fff;
            --bs-btn-active-bg: #212529;
            --bs-btn-active-border-color: #212529;
            --bs-btn-active-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
            --bs-btn-disabled-color: #212529;
            --bs-btn-disabled-bg: transparent;
            --bs-btn-disabled-border-color: #212529;
            --bs-gradient: none
        }

        .btn-link {
            --bs-btn-font-weight: 400;
            --bs-btn-color: var(--bs-link-color);
            --bs-btn-bg: transparent;
            --bs-btn-border-color: transparent;
            --bs-btn-hover-color: var(--bs-link-hover-color);
            --bs-btn-hover-border-color: transparent;
            --bs-btn-active-color: var(--bs-link-hover-color);
            --bs-btn-active-border-color: transparent;
            --bs-btn-disabled-color: #6c757d;
            --bs-btn-disabled-border-color: transparent;
            --bs-btn-box-shadow: 0 0 0 #000;
            --bs-btn-focus-shadow-rgb: 49, 132, 253;
            text-decoration: underline
        }

        .btn-link:focus-visible {
            color: var(--bs-btn-color)
        }

        .btn-link:hover {
            color: var(--bs-btn-hover-color)
        }

        .btn-group-lg>.btn,
        .btn-lg {
            --bs-btn-padding-y: 0.5rem;
            --bs-btn-padding-x: 1rem;
            --bs-btn-font-size: 1.25rem;
            --bs-btn-border-radius: var(--bs-border-radius-lg)
        }

        .btn-group-sm>.btn,
        .btn-sm {
            --bs-btn-padding-y: 0.25rem;
            --bs-btn-padding-x: 0.5rem;
            --bs-btn-font-size: 0.875rem;
            --bs-btn-border-radius: var(--bs-border-radius-sm)
        }

        .fade {
            transition: opacity .15s linear
        }

        @media (prefers-reduced-motion:reduce) {
            .fade {
                transition: none
            }
        }

        .fade:not(.show) {
            opacity: 0
        }

        .collapse:not(.show) {
            display: none
        }

        .collapsing {
            height: 0;
            overflow: hidden;
            transition: height .35s ease
        }

        @media (prefers-reduced-motion:reduce) {
            .collapsing {
                transition: none
            }
        }

        .collapsing.collapse-horizontal {
            width: 0;
            height: auto;
            transition: width .35s ease
        }

        @media (prefers-reduced-motion:reduce) {
            .collapsing.collapse-horizontal {
                transition: none
            }
        }

        .dropdown,
        .dropdown-center,
        .dropend,
        .dropstart,
        .dropup,
        .dropup-center {
            position: relative
        }

        .dropdown-toggle {
            white-space: nowrap
        }

        .dropdown-toggle::after {
            display: inline-block;
            margin-left: .255em;
            vertical-align: .255em;
            content: "";
            border-top: .3em solid;
            border-right: .3em solid transparent;
            border-bottom: 0;
            border-left: .3em solid transparent
        }

        .dropdown-toggle:empty::after {
            margin-left: 0
        }

        .dropdown-menu {
            --bs-dropdown-zindex: 1000;
            --bs-dropdown-min-width: 10rem;
            --bs-dropdown-padding-x: 0;
            --bs-dropdown-padding-y: 0.5rem;
            --bs-dropdown-spacer: 0.125rem;
            --bs-dropdown-font-size: 1rem;
            --bs-dropdown-color: var(--bs-body-color);
            --bs-dropdown-bg: var(--bs-body-bg);
            --bs-dropdown-border-color: var(--bs-border-color-translucent);
            --bs-dropdown-border-radius: var(--bs-border-radius);
            --bs-dropdown-border-width: var(--bs-border-width);
            --bs-dropdown-inner-border-radius: calc(var(--bs-border-radius) - var(--bs-border-width));
            --bs-dropdown-divider-bg: var(--bs-border-color-translucent);
            --bs-dropdown-divider-margin-y: 0.5rem;
            --bs-dropdown-box-shadow: 0 0.5rem 1rem rgba(0, 0, 0, 0.15);
            --bs-dropdown-link-color: var(--bs-body-color);
            --bs-dropdown-link-hover-color: var(--bs-body-color);
            --bs-dropdown-link-hover-bg: var(--bs-tertiary-bg);
            --bs-dropdown-link-active-color: #fff;
            --bs-dropdown-link-active-bg: #0d6efd;
            --bs-dropdown-link-disabled-color: var(--bs-tertiary-color);
            --bs-dropdown-item-padding-x: 1rem;
            --bs-dropdown-item-padding-y: 0.25rem;
            --bs-dropdown-header-color: #6c757d;
            --bs-dropdown-header-padding-x: 1rem;
            --bs-dropdown-header-padding-y: 0.5rem;
            position: absolute;
            z-index: var(--bs-dropdown-zindex);
            display: none;
            min-width: var(--bs-dropdown-min-width);
            padding: var(--bs-dropdown-padding-y) var(--bs-dropdown-padding-x);
            margin: 0;
            font-size: var(--bs-dropdown-font-size);
            color: var(--bs-dropdown-color);
            text-align: left;
            list-style: none;
            background-color: var(--bs-dropdown-bg);
            background-clip: padding-box;
            border: var(--bs-dropdown-border-width) solid var(--bs-dropdown-border-color);
            border-radius: var(--bs-dropdown-border-radius)
        }

        .dropdown-menu[data-bs-popper] {
            top: 100%;
            left: 0;
            margin-top: var(--bs-dropdown-spacer)
        }

        .dropdown-menu-start {
            --bs-position: start
        }

        .dropdown-menu-start[data-bs-popper] {
            right: auto;
            left: 0
        }

        .dropdown-menu-end {
            --bs-position: end
        }

        .dropdown-menu-end[data-bs-popper] {
            right: 0;
            left: auto
        }

        @media (min-width:576px) {
            .dropdown-menu-sm-start {
                --bs-position: start
            }

            .dropdown-menu-sm-start[data-bs-popper] {
                right: auto;
                left: 0
            }

            .dropdown-menu-sm-end {
                --bs-position: end
            }

            .dropdown-menu-sm-end[data-bs-popper] {
                right: 0;
                left: auto
            }
        }

        @media (min-width:768px) {
            .dropdown-menu-md-start {
                --bs-position: start
            }

            .dropdown-menu-md-start[data-bs-popper] {
                right: auto;
                left: 0
            }

            .dropdown-menu-md-end {
                --bs-position: end
            }

            .dropdown-menu-md-end[data-bs-popper] {
                right: 0;
                left: auto
            }
        }

        @media (min-width:992px) {
            .dropdown-menu-lg-start {
                --bs-position: start
            }

            .dropdown-menu-lg-start[data-bs-popper] {
                right: auto;
                left: 0
            }

            .dropdown-menu-lg-end {
                --bs-position: end
            }

            .dropdown-menu-lg-end[data-bs-popper] {
                right: 0;
                left: auto
            }
        }

        @media (min-width:1200px) {
            .dropdown-menu-xl-start {
                --bs-position: start
            }

            .dropdown-menu-xl-start[data-bs-popper] {
                right: auto;
                left: 0
            }

            .dropdown-menu-xl-end {
                --bs-position: end
            }

            .dropdown-menu-xl-end[data-bs-popper] {
                right: 0;
                left: auto
            }
        }

        @media (min-width:1400px) {
            .dropdown-menu-xxl-start {
                --bs-position: start
            }

            .dropdown-menu-xxl-start[data-bs-popper] {
                right: auto;
                left: 0
            }

            .dropdown-menu-xxl-end {
                --bs-position: end
            }

            .dropdown-menu-xxl-end[data-bs-popper] {
                right: 0;
                left: auto
            }
        }

        .dropup .dropdown-menu[data-bs-popper] {
            top: auto;
            bottom: 100%;
            margin-top: 0;
            margin-bottom: var(--bs-dropdown-spacer)
        }

        .dropup .dropdown-toggle::after {
            display: inline-block;
            margin-left: .255em;
            vertical-align: .255em;
            content: "";
            border-top: 0;
            border-right: .3em solid transparent;
            border-bottom: .3em solid;
            border-left: .3em solid transparent
        }

        .dropup .dropdown-toggle:empty::after {
            margin-left: 0
        }

        .dropend .dropdown-menu[data-bs-popper] {
            top: 0;
            right: auto;
            left: 100%;
            margin-top: 0;
            margin-left: var(--bs-dropdown-spacer)
        }

        .dropend .dropdown-toggle::after {
            display: inline-block;
            margin-left: .255em;
            vertical-align: .255em;
            content: "";
            border-top: .3em solid transparent;
            border-right: 0;
            border-bottom: .3em solid transparent;
            border-left: .3em solid
        }

        .dropend .dropdown-toggle:empty::after {
            margin-left: 0
        }

        .dropend .dropdown-toggle::after {
            vertical-align: 0
        }

        .dropstart .dropdown-menu[data-bs-popper] {
            top: 0;
            right: 100%;
            left: auto;
            margin-top: 0;
            margin-right: var(--bs-dropdown-spacer)
        }

        .dropstart .dropdown-toggle::after {
            display: inline-block;
            margin-left: .255em;
            vertical-align: .255em;
            content: ""
        }

        .dropstart .dropdown-toggle::after {
            display: none
        }

        .dropstart .dropdown-toggle::before {
            display: inline-block;
            margin-right: .255em;
            vertical-align: .255em;
            content: "";
            border-top: .3em solid transparent;
            border-right: .3em solid;
            border-bottom: .3em solid transparent
        }

        .dropstart .dropdown-toggle:empty::after {
            margin-left: 0
        }

        .dropstart .dropdown-toggle::before {
            vertical-align: 0
        }

        .dropdown-divider {
            height: 0;
            margin: var(--bs-dropdown-divider-margin-y) 0;
            overflow: hidden;
            border-top: 1px solid var(--bs-dropdown-divider-bg);
            opacity: 1
        }

        .dropdown-item {
            display: block;
            width: 100%;
            padding: var(--bs-dropdown-item-padding-y) var(--bs-dropdown-item-padding-x);
            clear: both;
            font-weight: 400;
            color: var(--bs-dropdown-link-color);
            text-align: inherit;
            text-decoration: none;
            white-space: nowrap;
            background-color: transparent;
            border: 0;
            border-radius: var(--bs-dropdown-item-border-radius, 0)
        }

        .dropdown-item:focus,
        .dropdown-item:hover {
            color: var(--bs-dropdown-link-hover-color);
            background-color: var(--bs-dropdown-link-hover-bg)
        }

        .dropdown-item.active,
        .dropdown-item:active {
            color: var(--bs-dropdown-link-active-color);
            text-decoration: none;
            background-color: var(--bs-dropdown-link-active-bg)
        }

        .dropdown-item.disabled,
        .dropdown-item:disabled {
            color: var(--bs-dropdown-link-disabled-color);
            pointer-events: none;
            background-color: transparent
        }

        .dropdown-menu.show {
            display: block
        }

        .dropdown-header {
            display: block;
            padding: var(--bs-dropdown-header-padding-y) var(--bs-dropdown-header-padding-x);
            margin-bottom: 0;
            font-size: .875rem;
            color: var(--bs-dropdown-header-color);
            white-space: nowrap
        }

        .dropdown-item-text {
            display: block;
            padding: var(--bs-dropdown-item-padding-y) var(--bs-dropdown-item-padding-x);
            color: var(--bs-dropdown-link-color)
        }

        .dropdown-menu-dark {
            --bs-dropdown-color: #dee2e6;
            --bs-dropdown-bg: #343a40;
            --bs-dropdown-border-color: var(--bs-border-color-translucent);
            --bs-dropdown-box-shadow: ;
            --bs-dropdown-link-color: #dee2e6;
            --bs-dropdown-link-hover-color: #fff;
            --bs-dropdown-divider-bg: var(--bs-border-color-translucent);
            --bs-dropdown-link-hover-bg: rgba(255, 255, 255, 0.15);
            --bs-dropdown-link-active-color: #fff;
            --bs-dropdown-link-active-bg: #0d6efd;
            --bs-dropdown-link-disabled-color: #adb5bd;
            --bs-dropdown-header-color: #adb5bd
        }

        .btn-group,
        .btn-group-vertical {
            position: relative;
            display: inline-flex;
            vertical-align: middle
        }

        .btn-group-vertical>.btn,
        .btn-group>.btn {
            position: relative;
            flex: 1 1 auto
        }

        .btn-group-vertical>.btn-check:checked+.btn,
        .btn-group-vertical>.btn-check:focus+.btn,
        .btn-group-vertical>.btn.active,
        .btn-group-vertical>.btn:active,
        .btn-group-vertical>.btn:focus,
        .btn-group-vertical>.btn:hover,
        .btn-group>.btn-check:checked+.btn,
        .btn-group>.btn-check:focus+.btn,
        .btn-group>.btn.active,
        .btn-group>.btn:active,
        .btn-group>.btn:focus,
        .btn-group>.btn:hover {
            z-index: 1
        }

        .btn-toolbar {
            display: flex;
            flex-wrap: wrap;
            justify-content: flex-start
        }

        .btn-toolbar .input-group {
            width: auto
        }

        .btn-group {
            border-radius: var(--bs-border-radius)
        }

        .btn-group>.btn-group:not(:first-child),
        .btn-group>:not(.btn-check:first-child)+.btn {
            margin-left: calc(var(--bs-border-width) * -1)
        }

        .btn-group>.btn-group:not(:last-child)>.btn,
        .btn-group>.btn.dropdown-toggle-split:first-child,
        .btn-group>.btn:not(:last-child):not(.dropdown-toggle) {
            border-top-right-radius: 0;
            border-bottom-right-radius: 0
        }

        .btn-group>.btn-group:not(:first-child)>.btn,
        .btn-group>.btn:nth-child(n+3),
        .btn-group>:not(.btn-check)+.btn {
            border-top-left-radius: 0;
            border-bottom-left-radius: 0
        }

        .dropdown-toggle-split {
            padding-right: .5625rem;
            padding-left: .5625rem
        }

        .dropdown-toggle-split::after,
        .dropend .dropdown-toggle-split::after,
        .dropup .dropdown-toggle-split::after {
            margin-left: 0
        }

        .dropstart .dropdown-toggle-split::before {
            margin-right: 0
        }

        .btn-group-sm>.btn+.dropdown-toggle-split,
        .btn-sm+.dropdown-toggle-split {
            padding-right: .375rem;
            padding-left: .375rem
        }

        .btn-group-lg>.btn+.dropdown-toggle-split,
        .btn-lg+.dropdown-toggle-split {
            padding-right: .75rem;
            padding-left: .75rem
        }

        .btn-group-vertical {
            flex-direction: column;
            align-items: flex-start;
            justify-content: center
        }

        .btn-group-vertical>.btn,
        .btn-group-vertical>.btn-group {
            width: 100%
        }

        .btn-group-vertical>.btn-group:not(:first-child),
        .btn-group-vertical>.btn:not(:first-child) {
            margin-top: calc(var(--bs-border-width) * -1)
        }

        .btn-group-vertical>.btn-group:not(:last-child)>.btn,
        .btn-group-vertical>.btn:not(:last-child):not(.dropdown-toggle) {
            border-bottom-right-radius: 0;
            border-bottom-left-radius: 0
        }

        .btn-group-vertical>.btn-group:not(:first-child)>.btn,
        .btn-group-vertical>.btn~.btn {
            border-top-left-radius: 0;
            border-top-right-radius: 0
        }

        .nav {
            --bs-nav-link-padding-x: 1rem;
            --bs-nav-link-padding-y: 0.5rem;
            --bs-nav-link-font-weight: ;
            --bs-nav-link-color: var(--bs-link-color);
            --bs-nav-link-hover-color: var(--bs-link-hover-color);
            --bs-nav-link-disabled-color: var(--bs-secondary-color);
            display: flex;
            flex-wrap: wrap;
            padding-left: 0;
            margin-bottom: 0;
            list-style: none
        }

        .nav-link {
            display: block;
            padding: var(--bs-nav-link-padding-y) var(--bs-nav-link-padding-x);
            font-size: var(--bs-nav-link-font-size);
            font-weight: var(--bs-nav-link-font-weight);
            color: var(--bs-nav-link-color);
            text-decoration: none;
            background: 0 0;
            border: 0;
            transition: color .15s ease-in-out, background-color .15s ease-in-out, border-color .15s ease-in-out
        }

        @media (prefers-reduced-motion:reduce) {
            .nav-link {
                transition: none
            }
        }

        .nav-link:focus,
        .nav-link:hover {
            color: var(--bs-nav-link-hover-color)
        }

        .nav-link:focus-visible {
            outline: 0;
            box-shadow: 0 0 0 .25rem rgba(13, 110, 253, .25)
        }

        .nav-link.disabled {
            color: var(--bs-nav-link-disabled-color);
            pointer-events: none;
            cursor: default
        }

        .nav-tabs {
            --bs-nav-tabs-border-width: var(--bs-border-width);
            --bs-nav-tabs-border-color: var(--bs-border-color);
            --bs-nav-tabs-border-radius: var(--bs-border-radius);
            --bs-nav-tabs-link-hover-border-color: var(--bs-secondary-bg) var(--bs-secondary-bg) var(--bs-border-color);
            --bs-nav-tabs-link-active-color: var(--bs-emphasis-color);
            --bs-nav-tabs-link-active-bg: var(--bs-body-bg);
            --bs-nav-tabs-link-active-border-color: var(--bs-border-color) var(--bs-border-color) var(--bs-body-bg);
            border-bottom: var(--bs-nav-tabs-border-width) solid var(--bs-nav-tabs-border-color)
        }

        .nav-tabs .nav-link {
            margin-bottom: calc(-1 * var(--bs-nav-tabs-border-width));
            border: var(--bs-nav-tabs-border-width) solid transparent;
            border-top-left-radius: var(--bs-nav-tabs-border-radius);
            border-top-right-radius: var(--bs-nav-tabs-border-radius)
        }

        .nav-tabs .nav-link:focus,
        .nav-tabs .nav-link:hover {
            isolation: isolate;
            border-color: var(--bs-nav-tabs-link-hover-border-color)
        }

        .nav-tabs .nav-link.disabled,
        .nav-tabs .nav-link:disabled {
            color: var(--bs-nav-link-disabled-color);
            background-color: transparent;
            border-color: transparent
        }

        .nav-tabs .nav-item.show .nav-link,
        .nav-tabs .nav-link.active {
            color: var(--bs-nav-tabs-link-active-color);
            background-color: var(--bs-nav-tabs-link-active-bg);
            border-color: var(--bs-nav-tabs-link-active-border-color)
        }

        .nav-tabs .dropdown-menu {
            margin-top: calc(-1 * var(--bs-nav-tabs-border-width));
            border-top-left-radius: 0;
            border-top-right-radius: 0
        }

        .nav-pills {
            --bs-nav-pills-border-radius: var(--bs-border-radius);
            --bs-nav-pills-link-active-color: #fff;
            --bs-nav-pills-link-active-bg: #0d6efd
        }

        .nav-pills .nav-link {
            border-radius: var(--bs-nav-pills-border-radius)
        }

        .nav-pills .nav-link:disabled {
            color: var(--bs-nav-link-disabled-color);
            background-color: transparent;
            border-color: transparent
        }

        .nav-pills .nav-link.active,
        .nav-pills .show>.nav-link {
            color: var(--bs-nav-pills-link-active-color);
            background-color: var(--bs-nav-pills-link-active-bg)
        }

        .nav-underline {
            --bs-nav-underline-gap: 1rem;
            --bs-nav-underline-border-width: 0.125rem;
            --bs-nav-underline-link-active-color: var(--bs-emphasis-color);
            gap: var(--bs-nav-underline-gap)
        }

        .nav-underline .nav-link {
            padding-right: 0;
            padding-left: 0;
            border-bottom: var(--bs-nav-underline-border-width) solid transparent
        }

        .nav-underline .nav-link:focus,
        .nav-underline .nav-link:hover {
            border-bottom-color: currentcolor
        }

        .nav-underline .nav-link.active,
        .nav-underline .show>.nav-link {
            font-weight: 700;
            color: var(--bs-nav-underline-link-active-color);
            border-bottom-color: currentcolor
        }

        .nav-fill .nav-item,
        .nav-fill>.nav-link {
            flex: 1 1 auto;
            text-align: center
        }

        .nav-justified .nav-item,
        .nav-justified>.nav-link {
            flex-basis: 0;
            flex-grow: 1;
            text-align: center
        }

        .nav-fill .nav-item .nav-link,
        .nav-justified .nav-item .nav-link {
            width: 100%
        }

        .tab-content>.tab-pane {
            display: none
        }

        .tab-content>.active {
            display: block
        }

        .navbar {
            --bs-navbar-padding-x: 0;
            --bs-navbar-padding-y: 0.5rem;
            --bs-navbar-color: rgba(var(--bs-emphasis-color-rgb), 0.65);
            --bs-navbar-hover-color: rgba(var(--bs-emphasis-color-rgb), 0.8);
            --bs-navbar-disabled-color: rgba(var(--bs-emphasis-color-rgb), 0.3);
            --bs-navbar-active-color: rgba(var(--bs-emphasis-color-rgb), 1);
            --bs-navbar-brand-padding-y: 0.3125rem;
            --bs-navbar-brand-margin-end: 1rem;
            --bs-navbar-brand-font-size: 1.25rem;
            --bs-navbar-brand-color: rgba(var(--bs-emphasis-color-rgb), 1);
            --bs-navbar-brand-hover-color: rgba(var(--bs-emphasis-color-rgb), 1);
            --bs-navbar-nav-link-padding-x: 0.5rem;
            --bs-navbar-toggler-padding-y: 0.25rem;
            --bs-navbar-toggler-padding-x: 0.75rem;
            --bs-navbar-toggler-font-size: 1.25rem;
            --bs-navbar-toggler-icon-bg: url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 30 30'%3e%3cpath stroke='rgba%2833, 37, 41, 0.75%29' stroke-linecap='round' stroke-miterlimit='10' stroke-width='2' d='M4 7h22M4 15h22M4 23h22'/%3e%3c/svg%3e");
            --bs-navbar-toggler-border-color: rgba(var(--bs-emphasis-color-rgb), 0.15);
            --bs-navbar-toggler-border-radius: var(--bs-border-radius);
            --bs-navbar-toggler-focus-width: 0.25rem;
            --bs-navbar-toggler-transition: box-shadow 0.15s ease-in-out;
            position: relative;
            display: flex;
            flex-wrap: wrap;
            align-items: center;
            justify-content: space-between;
            padding: var(--bs-navbar-padding-y) var(--bs-navbar-padding-x)
        }

        .navbar>.container,
        .navbar>.container-fluid,
        .navbar>.container-lg,
        .navbar>.container-md,
        .navbar>.container-sm,
        .navbar>.container-xl,
        .navbar>.container-xxl {
            display: flex;
            flex-wrap: inherit;
            align-items: center;
            justify-content: space-between
        }

        .navbar-brand {
            padding-top: var(--bs-navbar-brand-padding-y);
            padding-bottom: var(--bs-navbar-brand-padding-y);
            margin-right: var(--bs-navbar-brand-margin-end);
            font-size: var(--bs-navbar-brand-font-size);
            color: var(--bs-navbar-brand-color);
            text-decoration: none;
            white-space: nowrap
        }

        .navbar-brand:focus,
        .navbar-brand:hover {
            color: var(--bs-navbar-brand-hover-color)
        }

        .navbar-nav {
            --bs-nav-link-padding-x: 0;
            --bs-nav-link-padding-y: 0.5rem;
            --bs-nav-link-font-weight: ;
            --bs-nav-link-color: var(--bs-navbar-color);
            --bs-nav-link-hover-color: var(--bs-navbar-hover-color);
            --bs-nav-link-disabled-color: var(--bs-navbar-disabled-color);
            display: flex;
            flex-direction: column;
            padding-left: 0;
            margin-bottom: 0;
            list-style: none
        }

        .navbar-nav .nav-link.active,
        .navbar-nav .nav-link.show {
            color: white;
        }

        .navbar-nav .dropdown-menu {
            position: static
        }

        .navbar-text {
            padding-top: .5rem;
            padding-bottom: .5rem;
            color: var(--bs-navbar-color)
        }

        .navbar-text a,
        .navbar-text a:focus,
        .navbar-text a:hover {
            color: var(--bs-navbar-active-color)
        }

        .navbar-collapse {
            flex-basis: 100%;
            flex-grow: 1;
            align-items: center
        }

        .navbar-toggler {
            padding: var(--bs-navbar-toggler-padding-y) var(--bs-navbar-toggler-padding-x);
            font-size: var(--bs-navbar-toggler-font-size);
            line-height: 1;
            color: var(--bs-navbar-color);
            background-color: transparent;
            border: var(--bs-border-width) solid var(--bs-navbar-toggler-border-color);
            border-radius: var(--bs-navbar-toggler-border-radius);
            transition: var(--bs-navbar-toggler-transition)
        }

        @media (prefers-reduced-motion:reduce) {
            .navbar-toggler {
                transition: none
            }
        }

        .navbar-toggler:hover {
            text-decoration: none
        }

        .navbar-toggler:focus {
            text-decoration: none;
            outline: 0;
            box-shadow: 0 0 0 var(--bs-navbar-toggler-focus-width)
        }

        .navbar-toggler-icon {
            display: inline-block;
            width: 1.5em;
            height: 1.5em;
            vertical-align: middle;
            background-image: var(--bs-navbar-toggler-icon-bg);
            background-repeat: no-repeat;
            background-position: center;
            background-size: 100%
        }

        .navbar-nav-scroll {
            max-height: var(--bs-scroll-height, 75vh);
            overflow-y: auto
        }

        @media (min-width:576px) {
            .navbar-expand-sm {
                flex-wrap: nowrap;
                justify-content: flex-start
            }

            .navbar-expand-sm .navbar-nav {
                flex-direction: row
            }

            .navbar-expand-sm .navbar-nav .dropdown-menu {
                position: absolute
            }

            .navbar-expand-sm .navbar-nav .nav-link {
                padding-right: var(--bs-navbar-nav-link-padding-x);
                padding-left: var(--bs-navbar-nav-link-padding-x)
            }

            .navbar-expand-sm .navbar-nav-scroll {
                overflow: visible
            }

            .navbar-expand-sm .navbar-collapse {
                display: flex !important;
                flex-basis: auto
            }

            .navbar-expand-sm .navbar-toggler {
                display: none
            }

            .navbar-expand-sm .offcanvas {
                position: static;
                z-index: auto;
                flex-grow: 1;
                width: auto !important;
                height: auto !important;
                visibility: visible !important;
                background-color: transparent !important;
                border: 0 !important;
                transform: none !important;
                transition: none
            }

            .navbar-expand-sm .offcanvas .offcanvas-header {
                display: none
            }

            .navbar-expand-sm .offcanvas .offcanvas-body {
                display: flex;
                flex-grow: 0;
                padding: 0;
                overflow-y: visible
            }
        }

        @media (min-width:768px) {
            .navbar-expand-md {
                flex-wrap: nowrap;
                justify-content: flex-start
            }

            .navbar-expand-md .navbar-nav {
                flex-direction: row
            }

            .navbar-expand-md .navbar-nav .dropdown-menu {
                position: absolute
            }

            .navbar-expand-md .navbar-nav .nav-link {
                padding-right: var(--bs-navbar-nav-link-padding-x);
                padding-left: var(--bs-navbar-nav-link-padding-x)
            }

            .navbar-expand-md .navbar-nav-scroll {
                overflow: visible
            }

            .navbar-expand-md .navbar-collapse {
                display: flex !important;
                flex-basis: auto
            }

            .navbar-expand-md .navbar-toggler {
                display: none
            }

            .navbar-expand-md .offcanvas {
                position: static;
                z-index: auto;
                flex-grow: 1;
                width: auto !important;
                height: auto !important;
                visibility: visible !important;
                background-color: transparent !important;
                border: 0 !important;
                transform: none !important;
                transition: none
            }

            .navbar-expand-md .offcanvas .offcanvas-header {
                display: none
            }

            .navbar-expand-md .offcanvas .offcanvas-body {
                display: flex;
                flex-grow: 0;
                padding: 0;
                overflow-y: visible
            }
        }

        @media (min-width:992px) {
            .navbar-expand-lg {
                flex-wrap: nowrap;
                justify-content: flex-start
            }

            .navbar-expand-lg .navbar-nav {
                flex-direction: row
            }

            .navbar-expand-lg .navbar-nav .dropdown-menu {
                position: absolute
            }

            .navbar-expand-lg .navbar-nav .nav-link {
                padding-right: var(--bs-navbar-nav-link-padding-x);
                padding-left: var(--bs-navbar-nav-link-padding-x)
            }

            .navbar-expand-lg .navbar-nav-scroll {
                overflow: visible
            }

            .navbar-expand-lg .navbar-collapse {
                display: flex !important;
                flex-basis: auto
            }

            .navbar-expand-lg .navbar-toggler {
                display: none
            }

            .navbar-expand-lg .offcanvas {
                position: static;
                z-index: auto;
                flex-grow: 1;
                width: auto !important;
                height: auto !important;
                visibility: visible !important;
                background-color: transparent !important;
                border: 0 !important;
                transform: none !important;
                transition: none
            }

            .navbar-expand-lg .offcanvas .offcanvas-header {
                display: none
            }

            .navbar-expand-lg .offcanvas .offcanvas-body {
                display: flex;
                flex-grow: 0;
                padding: 0;
                overflow-y: visible
            }
        }

        @media (min-width:1200px) {
            .navbar-expand-xl {
                flex-wrap: nowrap;
                justify-content: flex-start
            }

            .navbar-expand-xl .navbar-nav {
                flex-direction: row
            }

            .navbar-expand-xl .navbar-nav .dropdown-menu {
                position: absolute
            }

            .navbar-expand-xl .navbar-nav .nav-link {
                padding-right: var(--bs-navbar-nav-link-padding-x);
                padding-left: var(--bs-navbar-nav-link-padding-x)
            }

            .navbar-expand-xl .navbar-nav-scroll {
                overflow: visible
            }

            .navbar-expand-xl .navbar-collapse {
                display: flex !important;
                flex-basis: auto
            }

            .navbar-expand-xl .navbar-toggler {
                display: none
            }

            .navbar-expand-xl .offcanvas {
                position: static;
                z-index: auto;
                flex-grow: 1;
                width: auto !important;
                height: auto !important;
                visibility: visible !important;
                background-color: transparent !important;
                border: 0 !important;
                transform: none !important;
                transition: none
            }

            .navbar-expand-xl .offcanvas .offcanvas-header {
                display: none
            }

            .navbar-expand-xl .offcanvas .offcanvas-body {
                display: flex;
                flex-grow: 0;
                padding: 0;
                overflow-y: visible
            }
        }

        @media (min-width:1400px) {
            .navbar-expand-xxl {
                flex-wrap: nowrap;
                justify-content: flex-start
            }

            .navbar-expand-xxl .navbar-nav {
                flex-direction: row
            }

            .navbar-expand-xxl .navbar-nav .dropdown-menu {
                position: absolute
            }

            .navbar-expand-xxl .navbar-nav .nav-link {
                padding-right: var(--bs-navbar-nav-link-padding-x);
                padding-left: var(--bs-navbar-nav-link-padding-x)
            }

            .navbar-expand-xxl .navbar-nav-scroll {
                overflow: visible
            }

            .navbar-expand-xxl .navbar-collapse {
                display: flex !important;
                flex-basis: auto
            }

            .navbar-expand-xxl .navbar-toggler {
                display: none
            }

            .navbar-expand-xxl .offcanvas {
                position: static;
                z-index: auto;
                flex-grow: 1;
                width: auto !important;
                height: auto !important;
                visibility: visible !important;
                background-color: transparent !important;
                border: 0 !important;
                transform: none !important;
                transition: none
            }

            .navbar-expand-xxl .offcanvas .offcanvas-header {
                display: none
            }

            .navbar-expand-xxl .offcanvas .offcanvas-body {
                display: flex;
                flex-grow: 0;
                padding: 0;
                overflow-y: visible
            }
        }

        .navbar-expand {
            flex-wrap: nowrap;
            justify-content: flex-start
        }

        .navbar-expand .navbar-nav {
            flex-direction: row
        }

        .navbar-expand .navbar-nav .dropdown-menu {
            position: absolute
        }

        .navbar-expand .navbar-nav .nav-link {
            padding-right: var(--bs-navbar-nav-link-padding-x);
            padding-left: var(--bs-navbar-nav-link-padding-x)
        }

        .navbar-expand .navbar-nav-scroll {
            overflow: visible
        }

        .navbar-expand .navbar-collapse {
            display: flex !important;
            flex-basis: auto
        }

        .navbar-expand .navbar-toggler {
            display: none
        }

        .navbar-expand .offcanvas {
            position: static;
            z-index: auto;
            flex-grow: 1;
            width: auto !important;
            height: auto !important;
            visibility: visible !important;
            background-color: transparent !important;
            border: 0 !important;
            transform: none !important;
            transition: none
        }

        .navbar-expand .offcanvas .offcanvas-header {
            display: none
        }

        .navbar-expand .offcanvas .offcanvas-body {
            display: flex;
            flex-grow: 0;
            padding: 0;
            overflow-y: visible
        }

        .navbar-dark,
        .navbar[data-bs-theme=dark] {
            --bs-navbar-color: rgba(255, 255, 255, 0.55);
            --bs-navbar-hover-color: rgba(255, 255, 255, 0.75);
            --bs-navbar-disabled-color: rgba(255, 255, 255, 0.25);
            --bs-navbar-active-color: #fff;
            --bs-navbar-brand-color: #fff;
            --bs-navbar-brand-hover-color: #fff;
            --bs-navbar-toggler-border-color: rgba(255, 255, 255, 0.1);
            --bs-navbar-toggler-icon-bg: url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 30 30'%3e%3cpath stroke='rgba%28255, 255, 255, 0.55%29' stroke-linecap='round' stroke-miterlimit='10' stroke-width='2' d='M4 7h22M4 15h22M4 23h22'/%3e%3c/svg%3e")
        }

        [data-bs-theme=dark] .navbar-toggler-icon {
            --bs-navbar-toggler-icon-bg: url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 30 30'%3e%3cpath stroke='rgba%28255, 255, 255, 0.55%29' stroke-linecap='round' stroke-miterlimit='10' stroke-width='2' d='M4 7h22M4 15h22M4 23h22'/%3e%3c/svg%3e")
        }

        .card {
            --bs-card-spacer-y: 1rem;
            --bs-card-spacer-x: 1rem;
            --bs-card-title-spacer-y: 0.5rem;
            --bs-card-title-color: ;
            --bs-card-subtitle-color: ;
            --bs-card-border-width: var(--bs-border-width);
            --bs-card-border-color: var(--bs-border-color-translucent);
            --bs-card-border-radius: var(--bs-border-radius);
            --bs-card-box-shadow: ;
            --bs-card-inner-border-radius: calc(var(--bs-border-radius) - (var(--bs-border-width)));
            --bs-card-cap-padding-y: 0.5rem;
            --bs-card-cap-padding-x: 1rem;
            --bs-card-cap-bg: rgba(var(--bs-body-color-rgb), 0.03);
            --bs-card-cap-color: ;
            --bs-card-height: ;
            --bs-card-color: ;
            --bs-card-bg: var(--bs-body-bg);
            --bs-card-img-overlay-padding: 1rem;
            --bs-card-group-margin: 0.75rem;
            position: relative;
            display: flex;
            flex-direction: column;
            min-width: 0;
            height: var(--bs-card-height);
            color: var(--bs-body-color);
            word-wrap: break-word;
            background-color: var(--bs-card-bg);
            background-clip: border-box;
            border: var(--bs-card-border-width) solid var(--bs-card-border-color);
            border-radius: var(--bs-card-border-radius)
        }

        .card>hr {
            margin-right: 0;
            margin-left: 0
        }

        .card>.list-group {
            border-top: inherit;
            border-bottom: inherit
        }

        .card>.list-group:first-child {
            border-top-width: 0;
            border-top-left-radius: var(--bs-card-inner-border-radius);
            border-top-right-radius: var(--bs-card-inner-border-radius)
        }

        .card>.list-group:last-child {
            border-bottom-width: 0;
            border-bottom-right-radius: var(--bs-card-inner-border-radius);
            border-bottom-left-radius: var(--bs-card-inner-border-radius)
        }

        .card>.card-header+.list-group,
        .card>.list-group+.card-footer {
            border-top: 0
        }

        .card-body {
            flex: 1 1 auto;
            padding: var(--bs-card-spacer-y) var(--bs-card-spacer-x);
            color: var(--bs-card-color)
        }

        .card-title {
            margin-bottom: var(--bs-card-title-spacer-y);
            color: var(--bs-card-title-color)
        }

        .card-subtitle {
            margin-top: calc(-.5 * var(--bs-card-title-spacer-y));
            margin-bottom: 0;
            color: var(--bs-card-subtitle-color)
        }

        .card-text:last-child {
            margin-bottom: 0
        }

        .card-link+.card-link {
            margin-left: var(--bs-card-spacer-x)
        }

        .card-header {
            padding: var(--bs-card-cap-padding-y) var(--bs-card-cap-padding-x);
            margin-bottom: 0;
            color: var(--bs-card-cap-color);
            background-color: var(--bs-card-cap-bg);
            border-bottom: var(--bs-card-border-width) solid var(--bs-card-border-color)
        }

        .card-header:first-child {
            border-radius: var(--bs-card-inner-border-radius) var(--bs-card-inner-border-radius) 0 0
        }

        .card-footer {
            padding: var(--bs-card-cap-padding-y) var(--bs-card-cap-padding-x);
            color: var(--bs-card-cap-color);
            background-color: var(--bs-card-cap-bg);
            border-top: var(--bs-card-border-width) solid var(--bs-card-border-color)
        }

        .card-footer:last-child {
            border-radius: 0 0 var(--bs-card-inner-border-radius) var(--bs-card-inner-border-radius)
        }

        .card-header-tabs {
            margin-right: calc(-.5 * var(--bs-card-cap-padding-x));
            margin-bottom: calc(-1 * var(--bs-card-cap-padding-y));
            margin-left: calc(-.5 * var(--bs-card-cap-padding-x));
            border-bottom: 0
        }

        .card-header-tabs .nav-link.active {
            background-color: var(--bs-card-bg);
            border-bottom-color: var(--bs-card-bg)
        }

        .card-header-pills {
            margin-right: calc(-.5 * var(--bs-card-cap-padding-x));
            margin-left: calc(-.5 * var(--bs-card-cap-padding-x))
        }

        .card-img-overlay {
            position: absolute;
            top: 0;
            right: 0;
            bottom: 0;
            left: 0;
            padding: var(--bs-card-img-overlay-padding);
            border-radius: var(--bs-card-inner-border-radius)
        }

        .card-img,
        .card-img-bottom,
        .card-img-top {
            width: 100%
        }

        .card-img,
        .card-img-top {
            border-top-left-radius: var(--bs-card-inner-border-radius);
            border-top-right-radius: var(--bs-card-inner-border-radius)
        }

        .card-img,
        .card-img-bottom {
            border-bottom-right-radius: var(--bs-card-inner-border-radius);
            border-bottom-left-radius: var(--bs-card-inner-border-radius)
        }

        .card-group>.card {
            margin-bottom: var(--bs-card-group-margin)
        }

        @media (min-width:576px) {
            .card-group {
                display: flex;
                flex-flow: row wrap
            }

            .card-group>.card {
                flex: 1 0 0%;
                margin-bottom: 0
            }

            .card-group>.card+.card {
                margin-left: 0;
                border-left: 0
            }

            .card-group>.card:not(:last-child) {
                border-top-right-radius: 0;
                border-bottom-right-radius: 0
            }

            .card-group>.card:not(:last-child) .card-header,
            .card-group>.card:not(:last-child) .card-img-top {
                border-top-right-radius: 0
            }

            .card-group>.card:not(:last-child) .card-footer,
            .card-group>.card:not(:last-child) .card-img-bottom {
                border-bottom-right-radius: 0
            }

            .card-group>.card:not(:first-child) {
                border-top-left-radius: 0;
                border-bottom-left-radius: 0
            }

            .card-group>.card:not(:first-child) .card-header,
            .card-group>.card:not(:first-child) .card-img-top {
                border-top-left-radius: 0
            }

            .card-group>.card:not(:first-child) .card-footer,
            .card-group>.card:not(:first-child) .card-img-bottom {
                border-bottom-left-radius: 0
            }
        }

        .accordion {
            --bs-accordion-color: var(--bs-body-color);
            --bs-accordion-bg: var(--bs-body-bg);
            --bs-accordion-transition: color 0.15s ease-in-out, background-color 0.15s ease-in-out, border-color 0.15s ease-in-out, box-shadow 0.15s ease-in-out, border-radius 0.15s ease;
            --bs-accordion-border-color: var(--bs-border-color);
            --bs-accordion-border-width: var(--bs-border-width);
            --bs-accordion-border-radius: var(--bs-border-radius);
            --bs-accordion-inner-border-radius: calc(var(--bs-border-radius) - (var(--bs-border-width)));
            --bs-accordion-btn-padding-x: 1.25rem;
            --bs-accordion-btn-padding-y: 1rem;
            --bs-accordion-btn-color: var(--bs-body-color);
            --bs-accordion-btn-bg: var(--bs-accordion-bg);
            --bs-accordion-btn-icon: url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 16 16' fill='%23212529'%3e%3cpath fill-rule='evenodd' d='M1.646 4.646a.5.5 0 0 1 .708 0L8 10.293l5.646-5.647a.5.5 0 0 1 .708.708l-6 6a.5.5 0 0 1-.708 0l-6-6a.5.5 0 0 1 0-.708z'/%3e%3c/svg%3e");
            --bs-accordion-btn-icon-width: 1.25rem;
            --bs-accordion-btn-icon-transform: rotate(-180deg);
            --bs-accordion-btn-icon-transition: transform 0.2s ease-in-out;
            --bs-accordion-btn-active-icon: url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 16 16' fill='%23052c65'%3e%3cpath fill-rule='evenodd' d='M1.646 4.646a.5.5 0 0 1 .708 0L8 10.293l5.646-5.647a.5.5 0 0 1 .708.708l-6 6a.5.5 0 0 1-.708 0l-6-6a.5.5 0 0 1 0-.708z'/%3e%3c/svg%3e");
            --bs-accordion-btn-focus-border-color: #86b7fe;
            --bs-accordion-btn-focus-box-shadow: 0 0 0 0.25rem rgba(13, 110, 253, 0.25);
            --bs-accordion-body-padding-x: 1.25rem;
            --bs-accordion-body-padding-y: 1rem;
            --bs-accordion-active-color: var(--bs-primary-text-emphasis);
            --bs-accordion-active-bg: var(--bs-primary-bg-subtle)
        }

        .accordion-button {
            position: relative;
            display: flex;
            align-items: center;
            width: 100%;
            padding: var(--bs-accordion-btn-padding-y) var(--bs-accordion-btn-padding-x);
            font-size: 1rem;
            color: var(--bs-accordion-btn-color);
            text-align: left;
            background-color: var(--bs-accordion-btn-bg);
            border: 0;
            border-radius: 0;
            overflow-anchor: none;
            transition: var(--bs-accordion-transition)
        }

        @media (prefers-reduced-motion:reduce) {
            .accordion-button {
                transition: none
            }
        }

        .accordion-button:not(.collapsed) {
            color: var(--bs-accordion-active-color);
            background-color: var(--bs-accordion-active-bg);
            box-shadow: inset 0 calc(-1 * var(--bs-accordion-border-width)) 0 var(--bs-accordion-border-color)
        }

        .accordion-button:not(.collapsed)::after {
            background-image: var(--bs-accordion-btn-active-icon);
            transform: var(--bs-accordion-btn-icon-transform)
        }

        .accordion-button::after {
            flex-shrink: 0;
            width: var(--bs-accordion-btn-icon-width);
            height: var(--bs-accordion-btn-icon-width);
            margin-left: auto;
            content: "";
            background-image: var(--bs-accordion-btn-icon);
            background-repeat: no-repeat;
            background-size: var(--bs-accordion-btn-icon-width);
            transition: var(--bs-accordion-btn-icon-transition)
        }

        @media (prefers-reduced-motion:reduce) {
            .accordion-button::after {
                transition: none
            }
        }

        .accordion-button:hover {
            z-index: 2
        }

        .accordion-button:focus {
            z-index: 3;
            border-color: var(--bs-accordion-btn-focus-border-color);
            outline: 0;
            box-shadow: var(--bs-accordion-btn-focus-box-shadow)
        }

        .accordion-header {
            margin-bottom: 0
        }

        .accordion-item {
            color: var(--bs-accordion-color);
            background-color: var(--bs-accordion-bg);
            border: var(--bs-accordion-border-width) solid var(--bs-accordion-border-color)
        }

        .accordion-item:first-of-type {
            border-top-left-radius: var(--bs-accordion-border-radius);
            border-top-right-radius: var(--bs-accordion-border-radius)
        }

        .accordion-item:first-of-type .accordion-button {
            border-top-left-radius: var(--bs-accordion-inner-border-radius);
            border-top-right-radius: var(--bs-accordion-inner-border-radius)
        }

        .accordion-item:not(:first-of-type) {
            border-top: 0
        }

        .accordion-item:last-of-type {
            border-bottom-right-radius: var(--bs-accordion-border-radius);
            border-bottom-left-radius: var(--bs-accordion-border-radius)
        }

        .accordion-item:last-of-type .accordion-button.collapsed {
            border-bottom-right-radius: var(--bs-accordion-inner-border-radius);
            border-bottom-left-radius: var(--bs-accordion-inner-border-radius)
        }

        .accordion-item:last-of-type .accordion-collapse {
            border-bottom-right-radius: var(--bs-accordion-border-radius);
            border-bottom-left-radius: var(--bs-accordion-border-radius)
        }

        .accordion-body {
            padding: var(--bs-accordion-body-padding-y) var(--bs-accordion-body-padding-x)
        }

        .accordion-flush .accordion-collapse {
            border-width: 0
        }

        .accordion-flush .accordion-item {
            border-right: 0;
            border-left: 0;
            border-radius: 0
        }

        .accordion-flush .accordion-item:first-child {
            border-top: 0
        }

        .accordion-flush .accordion-item:last-child {
            border-bottom: 0
        }

        .accordion-flush .accordion-item .accordion-button,
        .accordion-flush .accordion-item .accordion-button.collapsed {
            border-radius: 0
        }

        [data-bs-theme=dark] .accordion-button::after {
            --bs-accordion-btn-icon: url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 16 16' fill='%236ea8fe'%3e%3cpath fill-rule='evenodd' d='M1.646 4.646a.5.5 0 0 1 .708 0L8 10.293l5.646-5.647a.5.5 0 0 1 .708.708l-6 6a.5.5 0 0 1-.708 0l-6-6a.5.5 0 0 1 0-.708z'/%3e%3c/svg%3e");
            --bs-accordion-btn-active-icon: url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 16 16' fill='%236ea8fe'%3e%3cpath fill-rule='evenodd' d='M1.646 4.646a.5.5 0 0 1 .708 0L8 10.293l5.646-5.647a.5.5 0 0 1 .708.708l-6 6a.5.5 0 0 1-.708 0l-6-6a.5.5 0 0 1 0-.708z'/%3e%3c/svg%3e")
        }

        .breadcrumb {
            --bs-breadcrumb-padding-x: 0;
            --bs-breadcrumb-padding-y: 0;
            --bs-breadcrumb-margin-bottom: 1rem;
            --bs-breadcrumb-bg: ;
            --bs-breadcrumb-border-radius: ;
            --bs-breadcrumb-divider-color: var(--bs-secondary-color);
            --bs-breadcrumb-item-padding-x: 0.5rem;
            --bs-breadcrumb-item-active-color: var(--bs-secondary-color);
            display: flex;
            flex-wrap: wrap;
            padding: var(--bs-breadcrumb-padding-y) var(--bs-breadcrumb-padding-x);
            margin-bottom: var(--bs-breadcrumb-margin-bottom);
            font-size: var(--bs-breadcrumb-font-size);
            list-style: none;
            background-color: var(--bs-breadcrumb-bg);
            border-radius: var(--bs-breadcrumb-border-radius)
        }

        .breadcrumb-item+.breadcrumb-item {
            padding-left: var(--bs-breadcrumb-item-padding-x)
        }

        .breadcrumb-item+.breadcrumb-item::before {
            float: left;
            padding-right: var(--bs-breadcrumb-item-padding-x);
            color: var(--bs-breadcrumb-divider-color);
            content: var(--bs-breadcrumb-divider, "/")
        }

        .breadcrumb-item.active {
            color: var(--bs-breadcrumb-item-active-color)
        }

        .pagination {
            --bs-pagination-padding-x: 0.75rem;
            --bs-pagination-padding-y: 0.375rem;
            --bs-pagination-font-size: 1rem;
            --bs-pagination-color: var(--bs-link-color);
            --bs-pagination-bg: var(--bs-body-bg);
            --bs-pagination-border-width: var(--bs-border-width);
            --bs-pagination-border-color: var(--bs-border-color);
            --bs-pagination-border-radius: var(--bs-border-radius);
            --bs-pagination-hover-color: var(--bs-link-hover-color);
            --bs-pagination-hover-bg: var(--bs-tertiary-bg);
            --bs-pagination-hover-border-color: var(--bs-border-color);
            --bs-pagination-focus-color: var(--bs-link-hover-color);
            --bs-pagination-focus-bg: var(--bs-secondary-bg);
            --bs-pagination-focus-box-shadow: 0 0 0 0.25rem rgba(13, 110, 253, 0.25);
            --bs-pagination-active-color: #fff;
            --bs-pagination-active-bg: #0d6efd;
            --bs-pagination-active-border-color: #0d6efd;
            --bs-pagination-disabled-color: var(--bs-secondary-color);
            --bs-pagination-disabled-bg: var(--bs-secondary-bg);
            --bs-pagination-disabled-border-color: var(--bs-border-color);
            display: flex;
            padding-left: 0;
            list-style: none
        }

        .page-link {
            position: relative;
            display: block;
            padding: var(--bs-pagination-padding-y) var(--bs-pagination-padding-x);
            font-size: var(--bs-pagination-font-size);
            color: var(--bs-pagination-color);
            text-decoration: none;
            background-color: var(--bs-pagination-bg);
            border: var(--bs-pagination-border-width) solid var(--bs-pagination-border-color);
            transition: color .15s ease-in-out, background-color .15s ease-in-out, border-color .15s ease-in-out, box-shadow .15s ease-in-out
        }

        @media (prefers-reduced-motion:reduce) {
            .page-link {
                transition: none
            }
        }

        .page-link:hover {
            z-index: 2;
            color: var(--bs-pagination-hover-color);
            background-color: var(--bs-pagination-hover-bg);
            border-color: var(--bs-pagination-hover-border-color)
        }

        .page-link:focus {
            z-index: 3;
            color: var(--bs-pagination-focus-color);
            background-color: var(--bs-pagination-focus-bg);
            outline: 0;
            box-shadow: var(--bs-pagination-focus-box-shadow)
        }

        .active>.page-link,
        .page-link.active {
            z-index: 3;
            color: var(--bs-pagination-active-color);
            background-color: var(--bs-pagination-active-bg);
            border-color: var(--bs-pagination-active-border-color)
        }

        .disabled>.page-link,
        .page-link.disabled {
            color: var(--bs-pagination-disabled-color);
            pointer-events: none;
            background-color: var(--bs-pagination-disabled-bg);
            border-color: var(--bs-pagination-disabled-border-color)
        }

        .page-item:not(:first-child) .page-link {
            margin-left: calc(var(--bs-border-width) * -1)
        }

        .page-item:first-child .page-link {
            border-top-left-radius: var(--bs-pagination-border-radius);
            border-bottom-left-radius: var(--bs-pagination-border-radius)
        }

        .page-item:last-child .page-link {
            border-top-right-radius: var(--bs-pagination-border-radius);
            border-bottom-right-radius: var(--bs-pagination-border-radius)
        }

        .pagination-lg {
            --bs-pagination-padding-x: 1.5rem;
            --bs-pagination-padding-y: 0.75rem;
            --bs-pagination-font-size: 1.25rem;
            --bs-pagination-border-radius: var(--bs-border-radius-lg)
        }

        .pagination-sm {
            --bs-pagination-padding-x: 0.5rem;
            --bs-pagination-padding-y: 0.25rem;
            --bs-pagination-font-size: 0.875rem;
            --bs-pagination-border-radius: var(--bs-border-radius-sm)
        }

        .badge {
            --bs-badge-padding-x: 0.65em;
            --bs-badge-padding-y: 0.35em;
            --bs-badge-font-size: 0.75em;
            --bs-badge-font-weight: 700;
            --bs-badge-color: #fff;
            --bs-badge-border-radius: var(--bs-border-radius);
            display: inline-block;
            padding: var(--bs-badge-padding-y) var(--bs-badge-padding-x);
            font-size: var(--bs-badge-font-size);
            font-weight: var(--bs-badge-font-weight);
            line-height: 1;
            color: var(--bs-badge-color);
            text-align: center;
            white-space: nowrap;
            vertical-align: baseline;
            border-radius: var(--bs-badge-border-radius)
        }

        .badge:empty {
            display: none
        }

        .btn .badge {
            position: relative;
            top: -1px
        }

        .alert {
            --bs-alert-bg: transparent;
            --bs-alert-padding-x: 1rem;
            --bs-alert-padding-y: 1rem;
            --bs-alert-margin-bottom: 1rem;
            --bs-alert-color: inherit;
            --bs-alert-border-color: transparent;
            --bs-alert-border: var(--bs-border-width) solid var(--bs-alert-border-color);
            --bs-alert-border-radius: var(--bs-border-radius);
            --bs-alert-link-color: inherit;
            position: relative;
            padding: var(--bs-alert-padding-y) var(--bs-alert-padding-x);
            margin-bottom: var(--bs-alert-margin-bottom);
            color: var(--bs-alert-color);
            background-color: var(--bs-alert-bg);
            border: var(--bs-alert-border);
            border-radius: var(--bs-alert-border-radius)
        }

        .alert-heading {
            color: inherit
        }

        .alert-link {
            font-weight: 700;
            color: var(--bs-alert-link-color)
        }

        .alert-dismissible {
            padding-right: 3rem
        }

        .alert-dismissible .btn-close {
            position: absolute;
            top: 0;
            right: 0;
            z-index: 2;
            padding: 1.25rem 1rem
        }

        .alert-primary {
            --bs-alert-color: var(--bs-primary-text-emphasis);
            --bs-alert-bg: var(--bs-primary-bg-subtle);
            --bs-alert-border-color: var(--bs-primary-border-subtle);
            --bs-alert-link-color: var(--bs-primary-text-emphasis)
        }

        .alert-secondary {
            --bs-alert-color: var(--bs-secondary-text-emphasis);
            --bs-alert-bg: var(--bs-secondary-bg-subtle);
            --bs-alert-border-color: var(--bs-secondary-border-subtle);
            --bs-alert-link-color: var(--bs-secondary-text-emphasis)
        }

        .alert-success {
            --bs-alert-color: var(--bs-success-text-emphasis);
            --bs-alert-bg: var(--bs-success-bg-subtle);
            --bs-alert-border-color: var(--bs-success-border-subtle);
            --bs-alert-link-color: var(--bs-success-text-emphasis)
        }

        .alert-info {
            --bs-alert-color: var(--bs-info-text-emphasis);
            --bs-alert-bg: var(--bs-info-bg-subtle);
            --bs-alert-border-color: var(--bs-info-border-subtle);
            --bs-alert-link-color: var(--bs-info-text-emphasis)
        }

        .alert-warning {
            --bs-alert-color: var(--bs-warning-text-emphasis);
            --bs-alert-bg: var(--bs-warning-bg-subtle);
            --bs-alert-border-color: var(--bs-warning-border-subtle);
            --bs-alert-link-color: var(--bs-warning-text-emphasis)
        }

        .alert-danger {
            --bs-alert-color: var(--bs-danger-text-emphasis);
            --bs-alert-bg: var(--bs-danger-bg-subtle);
            --bs-alert-border-color: var(--bs-danger-border-subtle);
            --bs-alert-link-color: var(--bs-danger-text-emphasis)
        }

        .alert-light {
            --bs-alert-color: var(--bs-light-text-emphasis);
            --bs-alert-bg: var(--bs-light-bg-subtle);
            --bs-alert-border-color: var(--bs-light-border-subtle);
            --bs-alert-link-color: var(--bs-light-text-emphasis)
        }

        .alert-dark {
            --bs-alert-color: var(--bs-dark-text-emphasis);
            --bs-alert-bg: var(--bs-dark-bg-subtle);
            --bs-alert-border-color: var(--bs-dark-border-subtle);
            --bs-alert-link-color: var(--bs-dark-text-emphasis)
        }

        @keyframes progress-bar-stripes {
            0% {
                background-position-x: 1rem
            }
        }

        .progress,
        .progress-stacked {
            --bs-progress-height: 1rem;
            --bs-progress-font-size: 0.75rem;
            --bs-progress-bg: var(--bs-secondary-bg);
            --bs-progress-border-radius: var(--bs-border-radius);
            --bs-progress-box-shadow: var(--bs-box-shadow-inset);
            --bs-progress-bar-color: #fff;
            --bs-progress-bar-bg: #0d6efd;
            --bs-progress-bar-transition: width 0.6s ease;
            display: flex;
            height: var(--bs-progress-height);
            overflow: hidden;
            font-size: var(--bs-progress-font-size);
            background-color: var(--bs-progress-bg);
            border-radius: var(--bs-progress-border-radius)
        }

        .progress-bar {
            display: flex;
            flex-direction: column;
            justify-content: center;
            overflow: hidden;
            color: var(--bs-progress-bar-color);
            text-align: center;
            white-space: nowrap;
            background-color: var(--bs-progress-bar-bg);
            transition: var(--bs-progress-bar-transition)
        }

        @media (prefers-reduced-motion:reduce) {
            .progress-bar {
                transition: none
            }
        }

        .progress-bar-striped {
            background-image: linear-gradient(45deg, rgba(255, 255, 255, .15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, .15) 50%, rgba(255, 255, 255, .15) 75%, transparent 75%, transparent);
            background-size: var(--bs-progress-height) var(--bs-progress-height)
        }

        .progress-stacked>.progress {
            overflow: visible
        }

        .progress-stacked>.progress>.progress-bar {
            width: 100%
        }

        .progress-bar-animated {
            animation: 1s linear infinite progress-bar-stripes
        }

        @media (prefers-reduced-motion:reduce) {
            .progress-bar-animated {
                animation: none
            }
        }

        .list-group {
            --bs-list-group-color: var(--bs-body-color);
            --bs-list-group-bg: var(--bs-body-bg);
            --bs-list-group-border-color: var(--bs-border-color);
            --bs-list-group-border-width: var(--bs-border-width);
            --bs-list-group-border-radius: var(--bs-border-radius);
            --bs-list-group-item-padding-x: 1rem;
            --bs-list-group-item-padding-y: 0.5rem;
            --bs-list-group-action-color: var(--bs-secondary-color);
            --bs-list-group-action-hover-color: var(--bs-emphasis-color);
            --bs-list-group-action-hover-bg: var(--bs-tertiary-bg);
            --bs-list-group-action-active-color: var(--bs-body-color);
            --bs-list-group-action-active-bg: var(--bs-secondary-bg);
            --bs-list-group-disabled-color: var(--bs-secondary-color);
            --bs-list-group-disabled-bg: var(--bs-body-bg);
            --bs-list-group-active-color: #fff;
            --bs-list-group-active-bg: #0d6efd;
            --bs-list-group-active-border-color: #0d6efd;
            display: flex;
            flex-direction: column;
            padding-left: 0;
            margin-bottom: 0;
            border-radius: var(--bs-list-group-border-radius)
        }

        .list-group-numbered {
            list-style-type: none;
            counter-reset: section
        }

        .list-group-numbered>.list-group-item::before {
            content: counters(section, ".") ". ";
            counter-increment: section
        }

        .list-group-item-action {
            width: 100%;
            color: var(--bs-list-group-action-color);
            text-align: inherit
        }

        .list-group-item-action:focus,
        .list-group-item-action:hover {
            z-index: 1;
            color: var(--bs-list-group-action-hover-color);
            text-decoration: none;
            background-color: var(--bs-list-group-action-hover-bg)
        }

        .list-group-item-action:active {
            color: var(--bs-list-group-action-active-color);
            background-color: var(--bs-list-group-action-active-bg)
        }

        .list-group-item {
            position: relative;
            display: block;
            padding: var(--bs-list-group-item-padding-y) var(--bs-list-group-item-padding-x);
            color: var(--bs-list-group-color);
            text-decoration: none;
            background-color: var(--bs-list-group-bg);
            border: var(--bs-list-group-border-width) solid var(--bs-list-group-border-color)
        }

        .list-group-item:first-child {
            border-top-left-radius: inherit;
            border-top-right-radius: inherit
        }

        .list-group-item:last-child {
            border-bottom-right-radius: inherit;
            border-bottom-left-radius: inherit
        }

        .list-group-item.disabled,
        .list-group-item:disabled {
            color: var(--bs-list-group-disabled-color);
            pointer-events: none;
            background-color: var(--bs-list-group-disabled-bg)
        }

        .list-group-item.active {
            z-index: 2;
            color: var(--bs-list-group-active-color);
            background-color: var(--bs-list-group-active-bg);
            border-color: var(--bs-list-group-active-border-color)
        }

        .list-group-item+.list-group-item {
            border-top-width: 0
        }

        .list-group-item+.list-group-item.active {
            margin-top: calc(-1 * var(--bs-list-group-border-width));
            border-top-width: var(--bs-list-group-border-width)
        }

        .list-group-horizontal {
            flex-direction: row
        }

        .list-group-horizontal>.list-group-item:first-child:not(:last-child) {
            border-bottom-left-radius: var(--bs-list-group-border-radius);
            border-top-right-radius: 0
        }

        .list-group-horizontal>.list-group-item:last-child:not(:first-child) {
            border-top-right-radius: var(--bs-list-group-border-radius);
            border-bottom-left-radius: 0
        }

        .list-group-horizontal>.list-group-item.active {
            margin-top: 0
        }

        .list-group-horizontal>.list-group-item+.list-group-item {
            border-top-width: var(--bs-list-group-border-width);
            border-left-width: 0
        }

        .list-group-horizontal>.list-group-item+.list-group-item.active {
            margin-left: calc(-1 * var(--bs-list-group-border-width));
            border-left-width: var(--bs-list-group-border-width)
        }

        @media (min-width:576px) {
            .list-group-horizontal-sm {
                flex-direction: row
            }

            .list-group-horizontal-sm>.list-group-item:first-child:not(:last-child) {
                border-bottom-left-radius: var(--bs-list-group-border-radius);
                border-top-right-radius: 0
            }

            .list-group-horizontal-sm>.list-group-item:last-child:not(:first-child) {
                border-top-right-radius: var(--bs-list-group-border-radius);
                border-bottom-left-radius: 0
            }

            .list-group-horizontal-sm>.list-group-item.active {
                margin-top: 0
            }

            .list-group-horizontal-sm>.list-group-item+.list-group-item {
                border-top-width: var(--bs-list-group-border-width);
                border-left-width: 0
            }

            .list-group-horizontal-sm>.list-group-item+.list-group-item.active {
                margin-left: calc(-1 * var(--bs-list-group-border-width));
                border-left-width: var(--bs-list-group-border-width)
            }
        }

        @media (min-width:768px) {
            .list-group-horizontal-md {
                flex-direction: row
            }

            .list-group-horizontal-md>.list-group-item:first-child:not(:last-child) {
                border-bottom-left-radius: var(--bs-list-group-border-radius);
                border-top-right-radius: 0
            }

            .list-group-horizontal-md>.list-group-item:last-child:not(:first-child) {
                border-top-right-radius: var(--bs-list-group-border-radius);
                border-bottom-left-radius: 0
            }

            .list-group-horizontal-md>.list-group-item.active {
                margin-top: 0
            }

            .list-group-horizontal-md>.list-group-item+.list-group-item {
                border-top-width: var(--bs-list-group-border-width);
                border-left-width: 0
            }

            .list-group-horizontal-md>.list-group-item+.list-group-item.active {
                margin-left: calc(-1 * var(--bs-list-group-border-width));
                border-left-width: var(--bs-list-group-border-width)
            }
        }

        @media (min-width:992px) {
            .list-group-horizontal-lg {
                flex-direction: row
            }

            .list-group-horizontal-lg>.list-group-item:first-child:not(:last-child) {
                border-bottom-left-radius: var(--bs-list-group-border-radius);
                border-top-right-radius: 0
            }

            .list-group-horizontal-lg>.list-group-item:last-child:not(:first-child) {
                border-top-right-radius: var(--bs-list-group-border-radius);
                border-bottom-left-radius: 0
            }

            .list-group-horizontal-lg>.list-group-item.active {
                margin-top: 0
            }

            .list-group-horizontal-lg>.list-group-item+.list-group-item {
                border-top-width: var(--bs-list-group-border-width);
                border-left-width: 0
            }

            .list-group-horizontal-lg>.list-group-item+.list-group-item.active {
                margin-left: calc(-1 * var(--bs-list-group-border-width));
                border-left-width: var(--bs-list-group-border-width)
            }
        }

        @media (min-width:1200px) {
            .list-group-horizontal-xl {
                flex-direction: row
            }

            .list-group-horizontal-xl>.list-group-item:first-child:not(:last-child) {
                border-bottom-left-radius: var(--bs-list-group-border-radius);
                border-top-right-radius: 0
            }

            .list-group-horizontal-xl>.list-group-item:last-child:not(:first-child) {
                border-top-right-radius: var(--bs-list-group-border-radius);
                border-bottom-left-radius: 0
            }

            .list-group-horizontal-xl>.list-group-item.active {
                margin-top: 0
            }

            .list-group-horizontal-xl>.list-group-item+.list-group-item {
                border-top-width: var(--bs-list-group-border-width);
                border-left-width: 0
            }

            .list-group-horizontal-xl>.list-group-item+.list-group-item.active {
                margin-left: calc(-1 * var(--bs-list-group-border-width));
                border-left-width: var(--bs-list-group-border-width)
            }
        }

        @media (min-width:1400px) {
            .list-group-horizontal-xxl {
                flex-direction: row
            }

            .list-group-horizontal-xxl>.list-group-item:first-child:not(:last-child) {
                border-bottom-left-radius: var(--bs-list-group-border-radius);
                border-top-right-radius: 0
            }

            .list-group-horizontal-xxl>.list-group-item:last-child:not(:first-child) {
                border-top-right-radius: var(--bs-list-group-border-radius);
                border-bottom-left-radius: 0
            }

            .list-group-horizontal-xxl>.list-group-item.active {
                margin-top: 0
            }

            .list-group-horizontal-xxl>.list-group-item+.list-group-item {
                border-top-width: var(--bs-list-group-border-width);
                border-left-width: 0
            }

            .list-group-horizontal-xxl>.list-group-item+.list-group-item.active {
                margin-left: calc(-1 * var(--bs-list-group-border-width));
                border-left-width: var(--bs-list-group-border-width)
            }
        }

        .list-group-flush {
            border-radius: 0
        }

        .list-group-flush>.list-group-item {
            border-width: 0 0 var(--bs-list-group-border-width)
        }

        .list-group-flush>.list-group-item:last-child {
            border-bottom-width: 0
        }

        .list-group-item-primary {
            --bs-list-group-color: var(--bs-primary-text-emphasis);
            --bs-list-group-bg: var(--bs-primary-bg-subtle);
            --bs-list-group-border-color: var(--bs-primary-border-subtle);
            --bs-list-group-action-hover-color: var(--bs-emphasis-color);
            --bs-list-group-action-hover-bg: var(--bs-primary-border-subtle);
            --bs-list-group-action-active-color: var(--bs-emphasis-color);
            --bs-list-group-action-active-bg: var(--bs-primary-border-subtle);
            --bs-list-group-active-color: var(--bs-primary-bg-subtle);
            --bs-list-group-active-bg: var(--bs-primary-text-emphasis);
            --bs-list-group-active-border-color: var(--bs-primary-text-emphasis)
        }

        .list-group-item-secondary {
            --bs-list-group-color: var(--bs-secondary-text-emphasis);
            --bs-list-group-bg: var(--bs-secondary-bg-subtle);
            --bs-list-group-border-color: var(--bs-secondary-border-subtle);
            --bs-list-group-action-hover-color: var(--bs-emphasis-color);
            --bs-list-group-action-hover-bg: var(--bs-secondary-border-subtle);
            --bs-list-group-action-active-color: var(--bs-emphasis-color);
            --bs-list-group-action-active-bg: var(--bs-secondary-border-subtle);
            --bs-list-group-active-color: var(--bs-secondary-bg-subtle);
            --bs-list-group-active-bg: var(--bs-secondary-text-emphasis);
            --bs-list-group-active-border-color: var(--bs-secondary-text-emphasis)
        }

        .list-group-item-success {
            --bs-list-group-color: var(--bs-success-text-emphasis);
            --bs-list-group-bg: var(--bs-success-bg-subtle);
            --bs-list-group-border-color: var(--bs-success-border-subtle);
            --bs-list-group-action-hover-color: var(--bs-emphasis-color);
            --bs-list-group-action-hover-bg: var(--bs-success-border-subtle);
            --bs-list-group-action-active-color: var(--bs-emphasis-color);
            --bs-list-group-action-active-bg: var(--bs-success-border-subtle);
            --bs-list-group-active-color: var(--bs-success-bg-subtle);
            --bs-list-group-active-bg: var(--bs-success-text-emphasis);
            --bs-list-group-active-border-color: var(--bs-success-text-emphasis)
        }

        .list-group-item-info {
            --bs-list-group-color: var(--bs-info-text-emphasis);
            --bs-list-group-bg: var(--bs-info-bg-subtle);
            --bs-list-group-border-color: var(--bs-info-border-subtle);
            --bs-list-group-action-hover-color: var(--bs-emphasis-color);
            --bs-list-group-action-hover-bg: var(--bs-info-border-subtle);
            --bs-list-group-action-active-color: var(--bs-emphasis-color);
            --bs-list-group-action-active-bg: var(--bs-info-border-subtle);
            --bs-list-group-active-color: var(--bs-info-bg-subtle);
            --bs-list-group-active-bg: var(--bs-info-text-emphasis);
            --bs-list-group-active-border-color: var(--bs-info-text-emphasis)
        }

        .list-group-item-warning {
            --bs-list-group-color: var(--bs-warning-text-emphasis);
            --bs-list-group-bg: var(--bs-warning-bg-subtle);
            --bs-list-group-border-color: var(--bs-warning-border-subtle);
            --bs-list-group-action-hover-color: var(--bs-emphasis-color);
            --bs-list-group-action-hover-bg: var(--bs-warning-border-subtle);
            --bs-list-group-action-active-color: var(--bs-emphasis-color);
            --bs-list-group-action-active-bg: var(--bs-warning-border-subtle);
            --bs-list-group-active-color: var(--bs-warning-bg-subtle);
            --bs-list-group-active-bg: var(--bs-warning-text-emphasis);
            --bs-list-group-active-border-color: var(--bs-warning-text-emphasis)
        }

        .list-group-item-danger {
            --bs-list-group-color: var(--bs-danger-text-emphasis);
            --bs-list-group-bg: var(--bs-danger-bg-subtle);
            --bs-list-group-border-color: var(--bs-danger-border-subtle);
            --bs-list-group-action-hover-color: var(--bs-emphasis-color);
            --bs-list-group-action-hover-bg: var(--bs-danger-border-subtle);
            --bs-list-group-action-active-color: var(--bs-emphasis-color);
            --bs-list-group-action-active-bg: var(--bs-danger-border-subtle);
            --bs-list-group-active-color: var(--bs-danger-bg-subtle);
            --bs-list-group-active-bg: var(--bs-danger-text-emphasis);
            --bs-list-group-active-border-color: var(--bs-danger-text-emphasis)
        }

        .list-group-item-light {
            --bs-list-group-color: var(--bs-light-text-emphasis);
            --bs-list-group-bg: var(--bs-light-bg-subtle);
            --bs-list-group-border-color: var(--bs-light-border-subtle);
            --bs-list-group-action-hover-color: var(--bs-emphasis-color);
            --bs-list-group-action-hover-bg: var(--bs-light-border-subtle);
            --bs-list-group-action-active-color: var(--bs-emphasis-color);
            --bs-list-group-action-active-bg: var(--bs-light-border-subtle);
            --bs-list-group-active-color: var(--bs-light-bg-subtle);
            --bs-list-group-active-bg: var(--bs-light-text-emphasis);
            --bs-list-group-active-border-color: var(--bs-light-text-emphasis)
        }

        .list-group-item-dark {
            --bs-list-group-color: var(--bs-dark-text-emphasis);
            --bs-list-group-bg: var(--bs-dark-bg-subtle);
            --bs-list-group-border-color: var(--bs-dark-border-subtle);
            --bs-list-group-action-hover-color: var(--bs-emphasis-color);
            --bs-list-group-action-hover-bg: var(--bs-dark-border-subtle);
            --bs-list-group-action-active-color: var(--bs-emphasis-color);
            --bs-list-group-action-active-bg: var(--bs-dark-border-subtle);
            --bs-list-group-active-color: var(--bs-dark-bg-subtle);
            --bs-list-group-active-bg: var(--bs-dark-text-emphasis);
            --bs-list-group-active-border-color: var(--bs-dark-text-emphasis)
        }

        .btn-close {
            --bs-btn-close-color: #000;
            --bs-btn-close-bg: url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 16 16' fill='%23000'%3e%3cpath d='M.293.293a1 1 0 0 1 1.414 0L8 6.586 14.293.293a1 1 0 1 1 1.414 1.414L9.414 8l6.293 6.293a1 1 0 0 1-1.414 1.414L8 9.414l-6.293 6.293a1 1 0 0 1-1.414-1.414L6.586 8 .293 1.707a1 1 0 0 1 0-1.414z'/%3e%3c/svg%3e");
            --bs-btn-close-opacity: 0.5;
            --bs-btn-close-hover-opacity: 0.75;
            --bs-btn-close-focus-shadow: 0 0 0 0.25rem rgba(13, 110, 253, 0.25);
            --bs-btn-close-focus-opacity: 1;
            --bs-btn-close-disabled-opacity: 0.25;
            --bs-btn-close-white-filter: invert(1) grayscale(100%) brightness(200%);
            box-sizing: content-box;
            width: 1em;
            height: 1em;
            padding: .25em .25em;
            color: var(--bs-btn-close-color);
            background: transparent var(--bs-btn-close-bg) center/1em auto no-repeat;
            border: 0;
            border-radius: .375rem;
            opacity: var(--bs-btn-close-opacity)
        }

        .btn-close:hover {
            color: var(--bs-btn-close-color);
            text-decoration: none;
            opacity: var(--bs-btn-close-hover-opacity)
        }

        .btn-close:focus {
            outline: 0;
            box-shadow: var(--bs-btn-close-focus-shadow);
            opacity: var(--bs-btn-close-focus-opacity)
        }

        .btn-close.disabled,
        .btn-close:disabled {
            pointer-events: none;
            -webkit-user-select: none;
            -moz-user-select: none;
            user-select: none;
            opacity: var(--bs-btn-close-disabled-opacity)
        }

        .btn-close-white {
            filter: var(--bs-btn-close-white-filter)
        }

        [data-bs-theme=dark] .btn-close {
            filter: var(--bs-btn-close-white-filter)
        }

        .toast {
            --bs-toast-zindex: 1090;
            --bs-toast-padding-x: 0.75rem;
            --bs-toast-padding-y: 0.5rem;
            --bs-toast-spacing: 1.5rem;
            --bs-toast-max-width: 350px;
            --bs-toast-font-size: 0.875rem;
            --bs-toast-color: ;
            --bs-toast-bg: rgba(var(--bs-body-bg-rgb), 0.85);
            --bs-toast-border-width: var(--bs-border-width);
            --bs-toast-border-color: var(--bs-border-color-translucent);
            --bs-toast-border-radius: var(--bs-border-radius);
            --bs-toast-box-shadow: var(--bs-box-shadow);
            --bs-toast-header-color: var(--bs-secondary-color);
            --bs-toast-header-bg: rgba(var(--bs-body-bg-rgb), 0.85);
            --bs-toast-header-border-color: var(--bs-border-color-translucent);
            width: var(--bs-toast-max-width);
            max-width: 100%;
            font-size: var(--bs-toast-font-size);
            color: var(--bs-toast-color);
            pointer-events: auto;
            background-color: var(--bs-toast-bg);
            background-clip: padding-box;
            border: var(--bs-toast-border-width) solid var(--bs-toast-border-color);
            box-shadow: var(--bs-toast-box-shadow);
            border-radius: var(--bs-toast-border-radius)
        }

        .toast.showing {
            opacity: 0
        }

        .toast:not(.show) {
            display: none
        }

        .toast-container {
            --bs-toast-zindex: 1090;
            position: absolute;
            z-index: var(--bs-toast-zindex);
            width: -webkit-max-content;
            width: -moz-max-content;
            width: max-content;
            max-width: 100%;
            pointer-events: none
        }

        .toast-container>:not(:last-child) {
            margin-bottom: var(--bs-toast-spacing)
        }

        .toast-header {
            display: flex;
            align-items: center;
            padding: var(--bs-toast-padding-y) var(--bs-toast-padding-x);
            color: var(--bs-toast-header-color);
            background-color: var(--bs-toast-header-bg);
            background-clip: padding-box;
            border-bottom: var(--bs-toast-border-width) solid var(--bs-toast-header-border-color);
            border-top-left-radius: calc(var(--bs-toast-border-radius) - var(--bs-toast-border-width));
            border-top-right-radius: calc(var(--bs-toast-border-radius) - var(--bs-toast-border-width))
        }

        .toast-header .btn-close {
            margin-right: calc(-.5 * var(--bs-toast-padding-x));
            margin-left: var(--bs-toast-padding-x)
        }

        .toast-body {
            padding: var(--bs-toast-padding-x);
            word-wrap: break-word
        }

        .modal {
            --bs-modal-zindex: 1055;
            --bs-modal-width: 500px;
            --bs-modal-padding: 1rem;
            --bs-modal-margin: 0.5rem;
            --bs-modal-color: ;
            --bs-modal-bg: var(--bs-body-bg);
            --bs-modal-border-color: var(--bs-border-color-translucent);
            --bs-modal-border-width: var(--bs-border-width);
            --bs-modal-border-radius: var(--bs-border-radius-lg);
            --bs-modal-box-shadow: 0 0.125rem 0.25rem rgba(0, 0, 0, 0.075);
            --bs-modal-inner-border-radius: calc(var(--bs-border-radius-lg) - (var(--bs-border-width)));
            --bs-modal-header-padding-x: 1rem;
            --bs-modal-header-padding-y: 1rem;
            --bs-modal-header-padding: 1rem 1rem;
            --bs-modal-header-border-color: var(--bs-border-color);
            --bs-modal-header-border-width: var(--bs-border-width);
            --bs-modal-title-line-height: 1.5;
            --bs-modal-footer-gap: 0.5rem;
            --bs-modal-footer-bg: ;
            --bs-modal-footer-border-color: var(--bs-border-color);
            --bs-modal-footer-border-width: var(--bs-border-width);
            position: fixed;
            top: 0;
            left: 0;
            z-index: var(--bs-modal-zindex);
            display: none;
            width: 100%;
            height: 100%;
            overflow-x: hidden;
            overflow-y: auto;
            outline: 0
        }

        .modal-dialog {
            position: relative;
            width: auto;
            margin: var(--bs-modal-margin);
            pointer-events: none
        }

        .modal.fade .modal-dialog {
            transition: transform .3s ease-out;
            transform: translate(0, -50px)
        }

        @media (prefers-reduced-motion:reduce) {
            .modal.fade .modal-dialog {
                transition: none
            }
        }

        .modal.show .modal-dialog {
            transform: none
        }

        .modal.modal-static .modal-dialog {
            transform: scale(1.02)
        }

        .modal-dialog-scrollable {
            height: calc(100% - var(--bs-modal-margin) * 2)
        }

        .modal-dialog-scrollable .modal-content {
            max-height: 100%;
            overflow: hidden
        }

        .modal-dialog-scrollable .modal-body {
            overflow-y: auto
        }

        .modal-dialog-centered {
            display: flex;
            align-items: center;
            min-height: calc(100% - var(--bs-modal-margin) * 2)
        }

        .modal-content {
            position: relative;
            display: flex;
            flex-direction: column;
            width: 100%;
            color: var(--bs-modal-color);
            pointer-events: auto;
            background-color: var(--bs-modal-bg);
            background-clip: padding-box;
            border: var(--bs-modal-border-width) solid var(--bs-modal-border-color);
            border-radius: var(--bs-modal-border-radius);
            outline: 0
        }

        .modal-backdrop {
            --bs-backdrop-zindex: 1050;
            --bs-backdrop-bg: #000;
            --bs-backdrop-opacity: 0.5;
            position: fixed;
            top: 0;
            left: 0;
            z-index: var(--bs-backdrop-zindex);
            width: 100vw;
            height: 100vh;
            background-color: var(--bs-backdrop-bg)
        }

        .modal-backdrop.fade {
            opacity: 0
        }

        .modal-backdrop.show {
            opacity: var(--bs-backdrop-opacity)
        }

        .modal-header {
            display: flex;
            flex-shrink: 0;
            align-items: center;
            justify-content: space-between;
            padding: var(--bs-modal-header-padding);
            border-bottom: var(--bs-modal-header-border-width) solid var(--bs-modal-header-border-color);
            border-top-left-radius: var(--bs-modal-inner-border-radius);
            border-top-right-radius: var(--bs-modal-inner-border-radius)
        }

        .modal-header .btn-close {
            padding: calc(var(--bs-modal-header-padding-y) * .5) calc(var(--bs-modal-header-padding-x) * .5);
            margin: calc(-.5 * var(--bs-modal-header-padding-y)) calc(-.5 * var(--bs-modal-header-padding-x)) calc(-.5 * var(--bs-modal-header-padding-y)) auto
        }

        .modal-title {
            margin-bottom: 0;
            line-height: var(--bs-modal-title-line-height)
        }

        .modal-body {
            position: relative;
            flex: 1 1 auto;
            padding: var(--bs-modal-padding)
        }

        .modal-footer {
            display: flex;
            flex-shrink: 0;
            flex-wrap: wrap;
            align-items: center;
            justify-content: flex-end;
            padding: calc(var(--bs-modal-padding) - var(--bs-modal-footer-gap) * .5);
            background-color: var(--bs-modal-footer-bg);
            border-top: var(--bs-modal-footer-border-width) solid var(--bs-modal-footer-border-color);
            border-bottom-right-radius: var(--bs-modal-inner-border-radius);
            border-bottom-left-radius: var(--bs-modal-inner-border-radius)
        }

        .modal-footer>* {
            margin: calc(var(--bs-modal-footer-gap) * .5)
        }

        @media (min-width:576px) {
            .modal {
                --bs-modal-margin: 1.75rem;
                --bs-modal-box-shadow: 0 0.5rem 1rem rgba(0, 0, 0, 0.15)
            }

            .modal-dialog {
                max-width: var(--bs-modal-width);
                margin-right: auto;
                margin-left: auto
            }

            .modal-sm {
                --bs-modal-width: 300px
            }
        }

        @media (min-width:992px) {

            .modal-lg,
            .modal-xl {
                --bs-modal-width: 800px
            }
        }

        @media (min-width:1200px) {
            .modal-xl {
                --bs-modal-width: 1140px
            }
        }

        .modal-fullscreen {
            width: 100vw;
            max-width: none;
            height: 100%;
            margin: 0
        }

        .modal-fullscreen .modal-content {
            height: 100%;
            border: 0;
            border-radius: 0
        }

        .modal-fullscreen .modal-footer,
        .modal-fullscreen .modal-header {
            border-radius: 0
        }

        .modal-fullscreen .modal-body {
            overflow-y: auto
        }

        @media (max-width:575.98px) {
            .modal-fullscreen-sm-down {
                width: 100vw;
                max-width: none;
                height: 100%;
                margin: 0
            }

            .modal-fullscreen-sm-down .modal-content {
                height: 100%;
                border: 0;
                border-radius: 0
            }

            .modal-fullscreen-sm-down .modal-footer,
            .modal-fullscreen-sm-down .modal-header {
                border-radius: 0
            }

            .modal-fullscreen-sm-down .modal-body {
                overflow-y: auto
            }
        }

        @media (max-width:767.98px) {
            .modal-fullscreen-md-down {
                width: 100vw;
                max-width: none;
                height: 100%;
                margin: 0
            }

            .modal-fullscreen-md-down .modal-content {
                height: 100%;
                border: 0;
                border-radius: 0
            }

            .modal-fullscreen-md-down .modal-footer,
            .modal-fullscreen-md-down .modal-header {
                border-radius: 0
            }

            .modal-fullscreen-md-down .modal-body {
                overflow-y: auto
            }
        }

        @media (max-width:991.98px) {
            .modal-fullscreen-lg-down {
                width: 100vw;
                max-width: none;
                height: 100%;
                margin: 0
            }

            .modal-fullscreen-lg-down .modal-content {
                height: 100%;
                border: 0;
                border-radius: 0
            }

            .modal-fullscreen-lg-down .modal-footer,
            .modal-fullscreen-lg-down .modal-header {
                border-radius: 0
            }

            .modal-fullscreen-lg-down .modal-body {
                overflow-y: auto
            }
        }

        @media (max-width:1199.98px) {
            .modal-fullscreen-xl-down {
                width: 100vw;
                max-width: none;
                height: 100%;
                margin: 0
            }

            .modal-fullscreen-xl-down .modal-content {
                height: 100%;
                border: 0;
                border-radius: 0
            }

            .modal-fullscreen-xl-down .modal-footer,
            .modal-fullscreen-xl-down .modal-header {
                border-radius: 0
            }

            .modal-fullscreen-xl-down .modal-body {
                overflow-y: auto
            }
        }

        @media (max-width:1399.98px) {
            .modal-fullscreen-xxl-down {
                width: 100vw;
                max-width: none;
                height: 100%;
                margin: 0
            }

            .modal-fullscreen-xxl-down .modal-content {
                height: 100%;
                border: 0;
                border-radius: 0
            }

            .modal-fullscreen-xxl-down .modal-footer,
            .modal-fullscreen-xxl-down .modal-header {
                border-radius: 0
            }

            .modal-fullscreen-xxl-down .modal-body {
                overflow-y: auto
            }
        }

        .tooltip {
            --bs-tooltip-zindex: 1080;
            --bs-tooltip-max-width: 200px;
            --bs-tooltip-padding-x: 0.5rem;
            --bs-tooltip-padding-y: 0.25rem;
            --bs-tooltip-margin: ;
            --bs-tooltip-font-size: 0.875rem;
            --bs-tooltip-color: var(--bs-body-bg);
            --bs-tooltip-bg: var(--bs-emphasis-color);
            --bs-tooltip-border-radius: var(--bs-border-radius);
            --bs-tooltip-opacity: 0.9;
            --bs-tooltip-arrow-width: 0.8rem;
            --bs-tooltip-arrow-height: 0.4rem;
            z-index: var(--bs-tooltip-zindex);
            display: block;
            margin: var(--bs-tooltip-margin);
            font-family: var(--bs-font-sans-serif);
            font-style: normal;
            font-weight: 400;
            line-height: 1.5;
            text-align: left;
            text-align: start;
            text-decoration: none;
            text-shadow: none;
            text-transform: none;
            letter-spacing: normal;
            word-break: normal;
            white-space: normal;
            word-spacing: normal;
            line-break: auto;
            font-size: var(--bs-tooltip-font-size);
            word-wrap: break-word;
            opacity: 0
        }

        .tooltip.show {
            opacity: var(--bs-tooltip-opacity)
        }

        .tooltip .tooltip-arrow {
            display: block;
            width: var(--bs-tooltip-arrow-width);
            height: var(--bs-tooltip-arrow-height)
        }

        .tooltip .tooltip-arrow::before {
            position: absolute;
            content: "";
            border-color: transparent;
            border-style: solid
        }

        .bs-tooltip-auto[data-popper-placement^=top] .tooltip-arrow,
        .bs-tooltip-top .tooltip-arrow {
            bottom: calc(-1 * var(--bs-tooltip-arrow-height))
        }

        .bs-tooltip-auto[data-popper-placement^=top] .tooltip-arrow::before,
        .bs-tooltip-top .tooltip-arrow::before {
            top: -1px;
            border-width: var(--bs-tooltip-arrow-height) calc(var(--bs-tooltip-arrow-width) * .5) 0;
            border-top-color: var(--bs-tooltip-bg)
        }

        .bs-tooltip-auto[data-popper-placement^=right] .tooltip-arrow,
        .bs-tooltip-end .tooltip-arrow {
            left: calc(-1 * var(--bs-tooltip-arrow-height));
            width: var(--bs-tooltip-arrow-height);
            height: var(--bs-tooltip-arrow-width)
        }

        .bs-tooltip-auto[data-popper-placement^=right] .tooltip-arrow::before,
        .bs-tooltip-end .tooltip-arrow::before {
            right: -1px;
            border-width: calc(var(--bs-tooltip-arrow-width) * .5) var(--bs-tooltip-arrow-height) calc(var(--bs-tooltip-arrow-width) * .5) 0;
            border-right-color: var(--bs-tooltip-bg)
        }

        .bs-tooltip-auto[data-popper-placement^=bottom] .tooltip-arrow,
        .bs-tooltip-bottom .tooltip-arrow {
            top: calc(-1 * var(--bs-tooltip-arrow-height))
        }

        .bs-tooltip-auto[data-popper-placement^=bottom] .tooltip-arrow::before,
        .bs-tooltip-bottom .tooltip-arrow::before {
            bottom: -1px;
            border-width: 0 calc(var(--bs-tooltip-arrow-width) * .5) var(--bs-tooltip-arrow-height);
            border-bottom-color: var(--bs-tooltip-bg)
        }

        .bs-tooltip-auto[data-popper-placement^=left] .tooltip-arrow,
        .bs-tooltip-start .tooltip-arrow {
            right: calc(-1 * var(--bs-tooltip-arrow-height));
            width: var(--bs-tooltip-arrow-height);
            height: var(--bs-tooltip-arrow-width)
        }

        .bs-tooltip-auto[data-popper-placement^=left] .tooltip-arrow::before,
        .bs-tooltip-start .tooltip-arrow::before {
            left: -1px;
            border-width: calc(var(--bs-tooltip-arrow-width) * .5) 0 calc(var(--bs-tooltip-arrow-width) * .5) var(--bs-tooltip-arrow-height);
            border-left-color: var(--bs-tooltip-bg)
        }

        .tooltip-inner {
            max-width: var(--bs-tooltip-max-width);
            padding: var(--bs-tooltip-padding-y) var(--bs-tooltip-padding-x);
            color: var(--bs-tooltip-color);
            text-align: center;
            background-color: var(--bs-tooltip-bg);
            border-radius: var(--bs-tooltip-border-radius)
        }

        .popover {
            --bs-popover-zindex: 1070;
            --bs-popover-max-width: 276px;
            --bs-popover-font-size: 0.875rem;
            --bs-popover-bg: var(--bs-body-bg);
            --bs-popover-border-width: var(--bs-border-width);
            --bs-popover-border-color: var(--bs-border-color-translucent);
            --bs-popover-border-radius: var(--bs-border-radius-lg);
            --bs-popover-inner-border-radius: calc(var(--bs-border-radius-lg) - var(--bs-border-width));
            --bs-popover-box-shadow: 0 0.5rem 1rem rgba(0, 0, 0, 0.15);
            --bs-popover-header-padding-x: 1rem;
            --bs-popover-header-padding-y: 0.5rem;
            --bs-popover-header-font-size: 1rem;
            --bs-popover-header-color: inherit;
            --bs-popover-header-bg: var(--bs-secondary-bg);
            --bs-popover-body-padding-x: 1rem;
            --bs-popover-body-padding-y: 1rem;
            --bs-popover-body-color: var(--bs-body-color);
            --bs-popover-arrow-width: 1rem;
            --bs-popover-arrow-height: 0.5rem;
            --bs-popover-arrow-border: var(--bs-popover-border-color);
            z-index: var(--bs-popover-zindex);
            display: block;
            max-width: var(--bs-popover-max-width);
            font-family: var(--bs-font-sans-serif);
            font-style: normal;
            font-weight: 400;
            line-height: 1.5;
            text-align: left;
            text-align: start;
            text-decoration: none;
            text-shadow: none;
            text-transform: none;
            letter-spacing: normal;
            word-break: normal;
            white-space: normal;
            word-spacing: normal;
            line-break: auto;
            font-size: var(--bs-popover-font-size);
            word-wrap: break-word;
            background-color: var(--bs-popover-bg);
            background-clip: padding-box;
            border: var(--bs-popover-border-width) solid var(--bs-popover-border-color);
            border-radius: var(--bs-popover-border-radius)
        }

        .popover .popover-arrow {
            display: block;
            width: var(--bs-popover-arrow-width);
            height: var(--bs-popover-arrow-height)
        }

        .popover .popover-arrow::after,
        .popover .popover-arrow::before {
            position: absolute;
            display: block;
            content: "";
            border-color: transparent;
            border-style: solid;
            border-width: 0
        }

        .bs-popover-auto[data-popper-placement^=top]>.popover-arrow,
        .bs-popover-top>.popover-arrow {
            bottom: calc(-1 * (var(--bs-popover-arrow-height)) - var(--bs-popover-border-width))
        }

        .bs-popover-auto[data-popper-placement^=top]>.popover-arrow::after,
        .bs-popover-auto[data-popper-placement^=top]>.popover-arrow::before,
        .bs-popover-top>.popover-arrow::after,
        .bs-popover-top>.popover-arrow::before {
            border-width: var(--bs-popover-arrow-height) calc(var(--bs-popover-arrow-width) * .5) 0
        }

        .bs-popover-auto[data-popper-placement^=top]>.popover-arrow::before,
        .bs-popover-top>.popover-arrow::before {
            bottom: 0;
            border-top-color: var(--bs-popover-arrow-border)
        }

        .bs-popover-auto[data-popper-placement^=top]>.popover-arrow::after,
        .bs-popover-top>.popover-arrow::after {
            bottom: var(--bs-popover-border-width);
            border-top-color: var(--bs-popover-bg)
        }

        .bs-popover-auto[data-popper-placement^=right]>.popover-arrow,
        .bs-popover-end>.popover-arrow {
            left: calc(-1 * (var(--bs-popover-arrow-height)) - var(--bs-popover-border-width));
            width: var(--bs-popover-arrow-height);
            height: var(--bs-popover-arrow-width)
        }

        .bs-popover-auto[data-popper-placement^=right]>.popover-arrow::after,
        .bs-popover-auto[data-popper-placement^=right]>.popover-arrow::before,
        .bs-popover-end>.popover-arrow::after,
        .bs-popover-end>.popover-arrow::before {
            border-width: calc(var(--bs-popover-arrow-width) * .5) var(--bs-popover-arrow-height) calc(var(--bs-popover-arrow-width) * .5) 0
        }

        .bs-popover-auto[data-popper-placement^=right]>.popover-arrow::before,
        .bs-popover-end>.popover-arrow::before {
            left: 0;
            border-right-color: var(--bs-popover-arrow-border)
        }

        .bs-popover-auto[data-popper-placement^=right]>.popover-arrow::after,
        .bs-popover-end>.popover-arrow::after {
            left: var(--bs-popover-border-width);
            border-right-color: var(--bs-popover-bg)
        }

        .bs-popover-auto[data-popper-placement^=bottom]>.popover-arrow,
        .bs-popover-bottom>.popover-arrow {
            top: calc(-1 * (var(--bs-popover-arrow-height)) - var(--bs-popover-border-width))
        }

        .bs-popover-auto[data-popper-placement^=bottom]>.popover-arrow::after,
        .bs-popover-auto[data-popper-placement^=bottom]>.popover-arrow::before,
        .bs-popover-bottom>.popover-arrow::after,
        .bs-popover-bottom>.popover-arrow::before {
            border-width: 0 calc(var(--bs-popover-arrow-width) * .5) var(--bs-popover-arrow-height)
        }

        .bs-popover-auto[data-popper-placement^=bottom]>.popover-arrow::before,
        .bs-popover-bottom>.popover-arrow::before {
            top: 0;
            border-bottom-color: var(--bs-popover-arrow-border)
        }

        .bs-popover-auto[data-popper-placement^=bottom]>.popover-arrow::after,
        .bs-popover-bottom>.popover-arrow::after {
            top: var(--bs-popover-border-width);
            border-bottom-color: var(--bs-popover-bg)
        }

        .bs-popover-auto[data-popper-placement^=bottom] .popover-header::before,
        .bs-popover-bottom .popover-header::before {
            position: absolute;
            top: 0;
            left: 50%;
            display: block;
            width: var(--bs-popover-arrow-width);
            margin-left: calc(-.5 * var(--bs-popover-arrow-width));
            content: "";
            border-bottom: var(--bs-popover-border-width) solid var(--bs-popover-header-bg)
        }

        .bs-popover-auto[data-popper-placement^=left]>.popover-arrow,
        .bs-popover-start>.popover-arrow {
            right: calc(-1 * (var(--bs-popover-arrow-height)) - var(--bs-popover-border-width));
            width: var(--bs-popover-arrow-height);
            height: var(--bs-popover-arrow-width)
        }

        .bs-popover-auto[data-popper-placement^=left]>.popover-arrow::after,
        .bs-popover-auto[data-popper-placement^=left]>.popover-arrow::before,
        .bs-popover-start>.popover-arrow::after,
        .bs-popover-start>.popover-arrow::before {
            border-width: calc(var(--bs-popover-arrow-width) * .5) 0 calc(var(--bs-popover-arrow-width) * .5) var(--bs-popover-arrow-height)
        }

        .bs-popover-auto[data-popper-placement^=left]>.popover-arrow::before,
        .bs-popover-start>.popover-arrow::before {
            right: 0;
            border-left-color: var(--bs-popover-arrow-border)
        }

        .bs-popover-auto[data-popper-placement^=left]>.popover-arrow::after,
        .bs-popover-start>.popover-arrow::after {
            right: var(--bs-popover-border-width);
            border-left-color: var(--bs-popover-bg)
        }

        .popover-header {
            padding: var(--bs-popover-header-padding-y) var(--bs-popover-header-padding-x);
            margin-bottom: 0;
            font-size: var(--bs-popover-header-font-size);
            color: var(--bs-popover-header-color);
            background-color: var(--bs-popover-header-bg);
            border-bottom: var(--bs-popover-border-width) solid var(--bs-popover-border-color);
            border-top-left-radius: var(--bs-popover-inner-border-radius);
            border-top-right-radius: var(--bs-popover-inner-border-radius)
        }

        .popover-header:empty {
            display: none
        }

        .popover-body {
            padding: var(--bs-popover-body-padding-y) var(--bs-popover-body-padding-x);
            color: var(--bs-popover-body-color)
        }

        .carousel {
            position: relative
        }

        .carousel.pointer-event {
            touch-action: pan-y
        }

        .carousel-inner {
            position: relative;
            width: 100%;
            overflow: hidden
        }

        .carousel-inner::after {
            display: block;
            clear: both;
            content: ""
        }

        .carousel-item {
            position: relative;
            display: none;
            float: left;
            width: 100%;
            margin-right: -100%;
            -webkit-backface-visibility: hidden;
            backface-visibility: hidden;
            transition: transform .6s ease-in-out
        }

        @media (prefers-reduced-motion:reduce) {
            .carousel-item {
                transition: none
            }
        }

        .carousel-item-next,
        .carousel-item-prev,
        .carousel-item.active {
            display: block
        }

        .active.carousel-item-end,
        .carousel-item-next:not(.carousel-item-start) {
            transform: translateX(100%)
        }

        .active.carousel-item-start,
        .carousel-item-prev:not(.carousel-item-end) {
            transform: translateX(-100%)
        }

        .carousel-fade .carousel-item {
            opacity: 0;
            transition-property: opacity;
            transform: none
        }

        .carousel-fade .carousel-item-next.carousel-item-start,
        .carousel-fade .carousel-item-prev.carousel-item-end,
        .carousel-fade .carousel-item.active {
            z-index: 1;
            opacity: 1
        }

        .carousel-fade .active.carousel-item-end,
        .carousel-fade .active.carousel-item-start {
            z-index: 0;
            opacity: 0;
            transition: opacity 0s .6s
        }

        @media (prefers-reduced-motion:reduce) {

            .carousel-fade .active.carousel-item-end,
            .carousel-fade .active.carousel-item-start {
                transition: none
            }
        }

        .carousel-control-next,
        .carousel-control-prev {
            position: absolute;
            top: 0;
            bottom: 0;
            z-index: 1;
            display: flex;
            align-items: center;
            justify-content: center;
            width: 15%;
            padding: 0;
            color: #fff;
            text-align: center;
            background: 0 0;
            border: 0;
            opacity: .5;
            transition: opacity .15s ease
        }

        @media (prefers-reduced-motion:reduce) {

            .carousel-control-next,
            .carousel-control-prev {
                transition: none
            }
        }

        .carousel-control-next:focus,
        .carousel-control-next:hover,
        .carousel-control-prev:focus,
        .carousel-control-prev:hover {
            color: #fff;
            text-decoration: none;
            outline: 0;
            opacity: .9
        }

        .carousel-control-prev {
            left: 0
        }

        .carousel-control-next {
            right: 0
        }

        .carousel-control-next-icon,
        .carousel-control-prev-icon {
            display: inline-block;
            width: 2rem;
            height: 2rem;
            background-repeat: no-repeat;
            background-position: 50%;
            background-size: 100% 100%
        }

        .carousel-control-prev-icon {
            background-image: url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 16 16' fill='%23fff'%3e%3cpath d='M11.354 1.646a.5.5 0 0 1 0 .708L5.707 8l5.647 5.646a.5.5 0 0 1-.708.708l-6-6a.5.5 0 0 1 0-.708l6-6a.5.5 0 0 1 .708 0z'/%3e%3c/svg%3e")
        }

        .carousel-control-next-icon {
            background-image: url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 16 16' fill='%23fff'%3e%3cpath d='M4.646 1.646a.5.5 0 0 1 .708 0l6 6a.5.5 0 0 1 0 .708l-6 6a.5.5 0 0 1-.708-.708L10.293 8 4.646 2.354a.5.5 0 0 1 0-.708z'/%3e%3c/svg%3e")
        }

        .carousel-indicators {
            position: absolute;
            right: 0;
            bottom: 0;
            left: 0;
            z-index: 2;
            display: flex;
            justify-content: center;
            padding: 0;
            margin-right: 15%;
            margin-bottom: 1rem;
            margin-left: 15%
        }

        .carousel-indicators [data-bs-target] {
            box-sizing: content-box;
            flex: 0 1 auto;
            width: 30px;
            height: 3px;
            padding: 0;
            margin-right: 3px;
            margin-left: 3px;
            text-indent: -999px;
            cursor: pointer;
            background-color: #fff;
            background-clip: padding-box;
            border: 0;
            border-top: 10px solid transparent;
            border-bottom: 10px solid transparent;
            opacity: .5;
            transition: opacity .6s ease
        }

        @media (prefers-reduced-motion:reduce) {
            .carousel-indicators [data-bs-target] {
                transition: none
            }
        }

        .carousel-indicators .active {
            opacity: 1
        }

        .carousel-caption {
            position: absolute;
            right: 15%;
            bottom: 1.25rem;
            left: 15%;
            padding-top: 1.25rem;
            padding-bottom: 1.25rem;
            color: #fff;
            text-align: center
        }

        .carousel-dark .carousel-control-next-icon,
        .carousel-dark .carousel-control-prev-icon {
            filter: invert(1) grayscale(100)
        }

        .carousel-dark .carousel-indicators [data-bs-target] {
            background-color: #000
        }

        .carousel-dark .carousel-caption {
            color: #000
        }

        [data-bs-theme=dark] .carousel .carousel-control-next-icon,
        [data-bs-theme=dark] .carousel .carousel-control-prev-icon,
        [data-bs-theme=dark].carousel .carousel-control-next-icon,
        [data-bs-theme=dark].carousel .carousel-control-prev-icon {
            filter: invert(1) grayscale(100)
        }

        [data-bs-theme=dark] .carousel .carousel-indicators [data-bs-target],
        [data-bs-theme=dark].carousel .carousel-indicators [data-bs-target] {
            background-color: #000
        }

        [data-bs-theme=dark] .carousel .carousel-caption,
        [data-bs-theme=dark].carousel .carousel-caption {
            color: #000
        }

        .spinner-border,
        .spinner-grow {
            display: inline-block;
            width: var(--bs-spinner-width);
            height: var(--bs-spinner-height);
            vertical-align: var(--bs-spinner-vertical-align);
            border-radius: 50%;
            animation: var(--bs-spinner-animation-speed) linear infinite var(--bs-spinner-animation-name)
        }

        @keyframes spinner-border {
            to {
                transform: rotate(360deg)
            }
        }

        .spinner-border {
            --bs-spinner-width: 2rem;
            --bs-spinner-height: 2rem;
            --bs-spinner-vertical-align: -0.125em;
            --bs-spinner-border-width: 0.25em;
            --bs-spinner-animation-speed: 0.75s;
            --bs-spinner-animation-name: spinner-border;
            border: var(--bs-spinner-border-width) solid currentcolor;
            border-right-color: transparent
        }

        .spinner-border-sm {
            --bs-spinner-width: 1rem;
            --bs-spinner-height: 1rem;
            --bs-spinner-border-width: 0.2em
        }

        @keyframes spinner-grow {
            0% {
                transform: scale(0)
            }

            50% {
                opacity: 1;
                transform: none
            }
        }

        .spinner-grow {
            --bs-spinner-width: 2rem;
            --bs-spinner-height: 2rem;
            --bs-spinner-vertical-align: -0.125em;
            --bs-spinner-animation-speed: 0.75s;
            --bs-spinner-animation-name: spinner-grow;
            background-color: currentcolor;
            opacity: 0
        }

        .spinner-grow-sm {
            --bs-spinner-width: 1rem;
            --bs-spinner-height: 1rem
        }

        @media (prefers-reduced-motion:reduce) {

            .spinner-border,
            .spinner-grow {
                --bs-spinner-animation-speed: 1.5s
            }
        }

        .offcanvas,
        .offcanvas-lg,
        .offcanvas-md,
        .offcanvas-sm,
        .offcanvas-xl,
        .offcanvas-xxl {
            --bs-offcanvas-zindex: 1045;
            --bs-offcanvas-width: 400px;
            --bs-offcanvas-height: 30vh;
            --bs-offcanvas-padding-x: 1rem;
            --bs-offcanvas-padding-y: 1rem;
            --bs-offcanvas-color: var(--bs-body-color);
            --bs-offcanvas-bg: var(--bs-body-bg);
            --bs-offcanvas-border-width: var(--bs-border-width);
            --bs-offcanvas-border-color: var(--bs-border-color-translucent);
            --bs-offcanvas-box-shadow: 0 0.125rem 0.25rem rgba(0, 0, 0, 0.075);
            --bs-offcanvas-transition: transform 0.3s ease-in-out;
            --bs-offcanvas-title-line-height: 1.5
        }

        @media (max-width:575.98px) {
            .offcanvas-sm {
                position: fixed;
                bottom: 0;
                z-index: var(--bs-offcanvas-zindex);
                display: flex;
                flex-direction: column;
                max-width: 100%;
                color: var(--bs-offcanvas-color);
                visibility: hidden;
                background-color: var(--bs-offcanvas-bg);
                background-clip: padding-box;
                outline: 0;
                transition: var(--bs-offcanvas-transition)
            }
        }

        @media (max-width:575.98px) and (prefers-reduced-motion:reduce) {
            .offcanvas-sm {
                transition: none
            }
        }

        @media (max-width:575.98px) {
            .offcanvas-sm.offcanvas-start {
                top: 0;
                left: 0;
                width: var(--bs-offcanvas-width);
                border-right: var(--bs-offcanvas-border-width) solid var(--bs-offcanvas-border-color);
                transform: translateX(-100%)
            }

            .offcanvas-sm.offcanvas-end {
                top: 0;
                right: 0;
                width: var(--bs-offcanvas-width);
                border-left: var(--bs-offcanvas-border-width) solid var(--bs-offcanvas-border-color);
                transform: translateX(100%)
            }

            .offcanvas-sm.offcanvas-top {
                top: 0;
                right: 0;
                left: 0;
                height: var(--bs-offcanvas-height);
                max-height: 100%;
                border-bottom: var(--bs-offcanvas-border-width) solid var(--bs-offcanvas-border-color);
                transform: translateY(-100%)
            }

            .offcanvas-sm.offcanvas-bottom {
                right: 0;
                left: 0;
                height: var(--bs-offcanvas-height);
                max-height: 100%;
                border-top: var(--bs-offcanvas-border-width) solid var(--bs-offcanvas-border-color);
                transform: translateY(100%)
            }

            .offcanvas-sm.show:not(.hiding),
            .offcanvas-sm.showing {
                transform: none
            }

            .offcanvas-sm.hiding,
            .offcanvas-sm.show,
            .offcanvas-sm.showing {
                visibility: visible
            }
        }

        @media (min-width:576px) {
            .offcanvas-sm {
                --bs-offcanvas-height: auto;
                --bs-offcanvas-border-width: 0;
                background-color: transparent !important
            }

            .offcanvas-sm .offcanvas-header {
                display: none
            }

            .offcanvas-sm .offcanvas-body {
                display: flex;
                flex-grow: 0;
                padding: 0;
                overflow-y: visible;
                background-color: transparent !important
            }
        }

        @media (max-width:767.98px) {
            .offcanvas-md {
                position: fixed;
                bottom: 0;
                z-index: var(--bs-offcanvas-zindex);
                display: flex;
                flex-direction: column;
                max-width: 100%;
                color: var(--bs-offcanvas-color);
                visibility: hidden;
                background-color: var(--bs-offcanvas-bg);
                background-clip: padding-box;
                outline: 0;
                transition: var(--bs-offcanvas-transition)
            }
        }

        @media (max-width:767.98px) and (prefers-reduced-motion:reduce) {
            .offcanvas-md {
                transition: none
            }
        }

        @media (max-width:767.98px) {
            .offcanvas-md.offcanvas-start {
                top: 0;
                left: 0;
                width: var(--bs-offcanvas-width);
                border-right: var(--bs-offcanvas-border-width) solid var(--bs-offcanvas-border-color);
                transform: translateX(-100%)
            }

            .offcanvas-md.offcanvas-end {
                top: 0;
                right: 0;
                width: var(--bs-offcanvas-width);
                border-left: var(--bs-offcanvas-border-width) solid var(--bs-offcanvas-border-color);
                transform: translateX(100%)
            }

            .offcanvas-md.offcanvas-top {
                top: 0;
                right: 0;
                left: 0;
                height: var(--bs-offcanvas-height);
                max-height: 100%;
                border-bottom: var(--bs-offcanvas-border-width) solid var(--bs-offcanvas-border-color);
                transform: translateY(-100%)
            }

            .offcanvas-md.offcanvas-bottom {
                right: 0;
                left: 0;
                height: var(--bs-offcanvas-height);
                max-height: 100%;
                border-top: var(--bs-offcanvas-border-width) solid var(--bs-offcanvas-border-color);
                transform: translateY(100%)
            }

            .offcanvas-md.show:not(.hiding),
            .offcanvas-md.showing {
                transform: none
            }

            .offcanvas-md.hiding,
            .offcanvas-md.show,
            .offcanvas-md.showing {
                visibility: visible
            }
        }

        @media (min-width:768px) {
            .offcanvas-md {
                --bs-offcanvas-height: auto;
                --bs-offcanvas-border-width: 0;
                background-color: transparent !important
            }

            .offcanvas-md .offcanvas-header {
                display: none
            }

            .offcanvas-md .offcanvas-body {
                display: flex;
                flex-grow: 0;
                padding: 0;
                overflow-y: visible;
                background-color: transparent !important
            }
        }

        @media (max-width:991.98px) {
            .offcanvas-lg {
                position: fixed;
                bottom: 0;
                z-index: var(--bs-offcanvas-zindex);
                display: flex;
                flex-direction: column;
                max-width: 100%;
                color: var(--bs-offcanvas-color);
                visibility: hidden;
                background-color: var(--bs-offcanvas-bg);
                background-clip: padding-box;
                outline: 0;
                transition: var(--bs-offcanvas-transition)
            }
        }

        @media (max-width:991.98px) and (prefers-reduced-motion:reduce) {
            .offcanvas-lg {
                transition: none
            }
        }

        @media (max-width:991.98px) {
            .offcanvas-lg.offcanvas-start {
                top: 0;
                left: 0;
                width: var(--bs-offcanvas-width);
                border-right: var(--bs-offcanvas-border-width) solid var(--bs-offcanvas-border-color);
                transform: translateX(-100%)
            }

            .offcanvas-lg.offcanvas-end {
                top: 0;
                right: 0;
                width: var(--bs-offcanvas-width);
                border-left: var(--bs-offcanvas-border-width) solid var(--bs-offcanvas-border-color);
                transform: translateX(100%)
            }

            .offcanvas-lg.offcanvas-top {
                top: 0;
                right: 0;
                left: 0;
                height: var(--bs-offcanvas-height);
                max-height: 100%;
                border-bottom: var(--bs-offcanvas-border-width) solid var(--bs-offcanvas-border-color);
                transform: translateY(-100%)
            }

            .offcanvas-lg.offcanvas-bottom {
                right: 0;
                left: 0;
                height: var(--bs-offcanvas-height);
                max-height: 100%;
                border-top: var(--bs-offcanvas-border-width) solid var(--bs-offcanvas-border-color);
                transform: translateY(100%)
            }

            .offcanvas-lg.show:not(.hiding),
            .offcanvas-lg.showing {
                transform: none
            }

            .offcanvas-lg.hiding,
            .offcanvas-lg.show,
            .offcanvas-lg.showing {
                visibility: visible
            }
        }

        @media (min-width:992px) {
            .offcanvas-lg {
                --bs-offcanvas-height: auto;
                --bs-offcanvas-border-width: 0;
                background-color: transparent !important
            }

            .offcanvas-lg .offcanvas-header {
                display: none
            }

            .offcanvas-lg .offcanvas-body {
                display: flex;
                flex-grow: 0;
                padding: 0;
                overflow-y: visible;
                background-color: transparent !important
            }
        }

        @media (max-width:1199.98px) {
            .offcanvas-xl {
                position: fixed;
                bottom: 0;
                z-index: var(--bs-offcanvas-zindex);
                display: flex;
                flex-direction: column;
                max-width: 100%;
                color: var(--bs-offcanvas-color);
                visibility: hidden;
                background-color: var(--bs-offcanvas-bg);
                background-clip: padding-box;
                outline: 0;
                transition: var(--bs-offcanvas-transition)
            }
        }

        @media (max-width:1199.98px) and (prefers-reduced-motion:reduce) {
            .offcanvas-xl {
                transition: none
            }
        }

        @media (max-width:1199.98px) {
            .offcanvas-xl.offcanvas-start {
                top: 0;
                left: 0;
                width: var(--bs-offcanvas-width);
                border-right: var(--bs-offcanvas-border-width) solid var(--bs-offcanvas-border-color);
                transform: translateX(-100%)
            }

            .offcanvas-xl.offcanvas-end {
                top: 0;
                right: 0;
                width: var(--bs-offcanvas-width);
                border-left: var(--bs-offcanvas-border-width) solid var(--bs-offcanvas-border-color);
                transform: translateX(100%)
            }

            .offcanvas-xl.offcanvas-top {
                top: 0;
                right: 0;
                left: 0;
                height: var(--bs-offcanvas-height);
                max-height: 100%;
                border-bottom: var(--bs-offcanvas-border-width) solid var(--bs-offcanvas-border-color);
                transform: translateY(-100%)
            }

            .offcanvas-xl.offcanvas-bottom {
                right: 0;
                left: 0;
                height: var(--bs-offcanvas-height);
                max-height: 100%;
                border-top: var(--bs-offcanvas-border-width) solid var(--bs-offcanvas-border-color);
                transform: translateY(100%)
            }

            .offcanvas-xl.show:not(.hiding),
            .offcanvas-xl.showing {
                transform: none
            }

            .offcanvas-xl.hiding,
            .offcanvas-xl.show,
            .offcanvas-xl.showing {
                visibility: visible
            }
        }

        @media (min-width:1200px) {
            .offcanvas-xl {
                --bs-offcanvas-height: auto;
                --bs-offcanvas-border-width: 0;
                background-color: transparent !important
            }

            .offcanvas-xl .offcanvas-header {
                display: none
            }

            .offcanvas-xl .offcanvas-body {
                display: flex;
                flex-grow: 0;
                padding: 0;
                overflow-y: visible;
                background-color: transparent !important
            }
        }

        @media (max-width:1399.98px) {
            .offcanvas-xxl {
                position: fixed;
                bottom: 0;
                z-index: var(--bs-offcanvas-zindex);
                display: flex;
                flex-direction: column;
                max-width: 100%;
                color: var(--bs-offcanvas-color);
                visibility: hidden;
                background-color: var(--bs-offcanvas-bg);
                background-clip: padding-box;
                outline: 0;
                transition: var(--bs-offcanvas-transition)
            }
        }

        @media (max-width:1399.98px) and (prefers-reduced-motion:reduce) {
            .offcanvas-xxl {
                transition: none
            }
        }

        @media (max-width:1399.98px) {
            .offcanvas-xxl.offcanvas-start {
                top: 0;
                left: 0;
                width: var(--bs-offcanvas-width);
                border-right: var(--bs-offcanvas-border-width) solid var(--bs-offcanvas-border-color);
                transform: translateX(-100%)
            }

            .offcanvas-xxl.offcanvas-end {
                top: 0;
                right: 0;
                width: var(--bs-offcanvas-width);
                border-left: var(--bs-offcanvas-border-width) solid var(--bs-offcanvas-border-color);
                transform: translateX(100%)
            }

            .offcanvas-xxl.offcanvas-top {
                top: 0;
                right: 0;
                left: 0;
                height: var(--bs-offcanvas-height);
                max-height: 100%;
                border-bottom: var(--bs-offcanvas-border-width) solid var(--bs-offcanvas-border-color);
                transform: translateY(-100%)
            }

            .offcanvas-xxl.offcanvas-bottom {
                right: 0;
                left: 0;
                height: var(--bs-offcanvas-height);
                max-height: 100%;
                border-top: var(--bs-offcanvas-border-width) solid var(--bs-offcanvas-border-color);
                transform: translateY(100%)
            }

            .offcanvas-xxl.show:not(.hiding),
            .offcanvas-xxl.showing {
                transform: none
            }

            .offcanvas-xxl.hiding,
            .offcanvas-xxl.show,
            .offcanvas-xxl.showing {
                visibility: visible
            }
        }

        @media (min-width:1400px) {
            .offcanvas-xxl {
                --bs-offcanvas-height: auto;
                --bs-offcanvas-border-width: 0;
                background-color: transparent !important
            }

            .offcanvas-xxl .offcanvas-header {
                display: none
            }

            .offcanvas-xxl .offcanvas-body {
                display: flex;
                flex-grow: 0;
                padding: 0;
                overflow-y: visible;
                background-color: transparent !important
            }
        }

        .offcanvas {
            position: fixed;
            bottom: 0;
            z-index: var(--bs-offcanvas-zindex);
            display: flex;
            flex-direction: column;
            max-width: 100%;
            color: var(--bs-offcanvas-color);
            visibility: hidden;
            background-color: var(--bs-offcanvas-bg);
            background-clip: padding-box;
            outline: 0;
            transition: var(--bs-offcanvas-transition)
        }

        @media (prefers-reduced-motion:reduce) {
            .offcanvas {
                transition: none
            }
        }

        .offcanvas.offcanvas-start {
            top: 0;
            left: 0;
            width: var(--bs-offcanvas-width);
            border-right: var(--bs-offcanvas-border-width) solid var(--bs-offcanvas-border-color);
            transform: translateX(-100%)
        }

        .offcanvas.offcanvas-end {
            top: 0;
            right: 0;
            width: var(--bs-offcanvas-width);
            border-left: var(--bs-offcanvas-border-width) solid var(--bs-offcanvas-border-color);
            transform: translateX(100%)
        }

        .offcanvas.offcanvas-top {
            top: 0;
            right: 0;
            left: 0;
            height: var(--bs-offcanvas-height);
            max-height: 100%;
            border-bottom: var(--bs-offcanvas-border-width) solid var(--bs-offcanvas-border-color);
            transform: translateY(-100%)
        }

        .offcanvas.offcanvas-bottom {
            right: 0;
            left: 0;
            height: var(--bs-offcanvas-height);
            max-height: 100%;
            border-top: var(--bs-offcanvas-border-width) solid var(--bs-offcanvas-border-color);
            transform: translateY(100%)
        }

        .offcanvas.show:not(.hiding),
        .offcanvas.showing {
            transform: none
        }

        .offcanvas.hiding,
        .offcanvas.show,
        .offcanvas.showing {
            visibility: visible
        }

        .offcanvas-backdrop {
            position: fixed;
            top: 0;
            left: 0;
            z-index: 1040;
            width: 100vw;
            height: 100vh;
            background-color: #000
        }

        .offcanvas-backdrop.fade {
            opacity: 0
        }

        .offcanvas-backdrop.show {
            opacity: .5
        }

        .offcanvas-header {
            display: flex;
            align-items: center;
            justify-content: space-between;
            padding: var(--bs-offcanvas-padding-y) var(--bs-offcanvas-padding-x)
        }

        .offcanvas-header .btn-close {
            padding: calc(var(--bs-offcanvas-padding-y) * .5) calc(var(--bs-offcanvas-padding-x) * .5);
            margin-top: calc(-.5 * var(--bs-offcanvas-padding-y));
            margin-right: calc(-.5 * var(--bs-offcanvas-padding-x));
            margin-bottom: calc(-.5 * var(--bs-offcanvas-padding-y))
        }

        .offcanvas-title {
            margin-bottom: 0;
            line-height: var(--bs-offcanvas-title-line-height)
        }

        .offcanvas-body {
            flex-grow: 1;
            padding: var(--bs-offcanvas-padding-y) var(--bs-offcanvas-padding-x);
            overflow-y: auto
        }

        .placeholder {
            display: inline-block;
            min-height: 1em;
            vertical-align: middle;
            cursor: wait;
            background-color: currentcolor;
            opacity: .5
        }

        .placeholder.btn::before {
            display: inline-block;
            content: ""
        }

        .placeholder-xs {
            min-height: .6em
        }

        .placeholder-sm {
            min-height: .8em
        }

        .placeholder-lg {
            min-height: 1.2em
        }

        .placeholder-glow .placeholder {
            animation: placeholder-glow 2s ease-in-out infinite
        }

        @keyframes placeholder-glow {
            50% {
                opacity: .2
            }
        }

        .placeholder-wave {
            -webkit-mask-image: linear-gradient(130deg, #000 55%, rgba(0, 0, 0, 0.8) 75%, #000 95%);
            mask-image: linear-gradient(130deg, #000 55%, rgba(0, 0, 0, 0.8) 75%, #000 95%);
            -webkit-mask-size: 200% 100%;
            mask-size: 200% 100%;
            animation: placeholder-wave 2s linear infinite
        }

        @keyframes placeholder-wave {
            100% {
                -webkit-mask-position: -200% 0%;
                mask-position: -200% 0%
            }
        }

        .clearfix::after {
            display: block;
            clear: both;
            content: ""
        }

        .text-bg-primary {
            color: #fff !important;
            background-color: RGBA(13, 110, 253, var(--bs-bg-opacity, 1)) !important
        }

        .text-bg-secondary {
            color: #fff !important;
            background-color: RGBA(108, 117, 125, var(--bs-bg-opacity, 1)) !important
        }

        .text-bg-success {
            color: #fff !important;
            background-color: RGBA(25, 135, 84, var(--bs-bg-opacity, 1)) !important
        }

        .text-bg-info {
            color: #000 !important;
            background-color: RGBA(13, 202, 240, var(--bs-bg-opacity, 1)) !important
        }

        .text-bg-warning {
            color: #000 !important;
            background-color: RGBA(255, 193, 7, var(--bs-bg-opacity, 1)) !important
        }

        .text-bg-danger {
            color: #fff !important;
            background-color: RGBA(220, 53, 69, var(--bs-bg-opacity, 1)) !important
        }

        .text-bg-light {
            color: #000 !important;
            background-color: RGBA(248, 249, 250, var(--bs-bg-opacity, 1)) !important
        }

        .text-bg-dark {
            color: #fff !important;
            background-color: RGBA(33, 37, 41, var(--bs-bg-opacity, 1)) !important
        }

        .link-primary {
            color: RGBA(var(--bs-primary-rgb), var(--bs-link-opacity, 1)) !important;
            -webkit-text-decoration-color: RGBA(var(--bs-primary-rgb), var(--bs-link-underline-opacity, 1)) !important;
            text-decoration-color: RGBA(var(--bs-primary-rgb), var(--bs-link-underline-opacity, 1)) !important
        }

        .link-primary:focus,
        .link-primary:hover {
            color: RGBA(10, 88, 202, var(--bs-link-opacity, 1)) !important;
            -webkit-text-decoration-color: RGBA(10, 88, 202, var(--bs-link-underline-opacity, 1)) !important;
            text-decoration-color: RGBA(10, 88, 202, var(--bs-link-underline-opacity, 1)) !important
        }

        .link-secondary {
            color: RGBA(var(--bs-secondary-rgb), var(--bs-link-opacity, 1)) !important;
            -webkit-text-decoration-color: RGBA(var(--bs-secondary-rgb), var(--bs-link-underline-opacity, 1)) !important;
            text-decoration-color: RGBA(var(--bs-secondary-rgb), var(--bs-link-underline-opacity, 1)) !important
        }

        .link-secondary:focus,
        .link-secondary:hover {
            color: RGBA(86, 94, 100, var(--bs-link-opacity, 1)) !important;
            -webkit-text-decoration-color: RGBA(86, 94, 100, var(--bs-link-underline-opacity, 1)) !important;
            text-decoration-color: RGBA(86, 94, 100, var(--bs-link-underline-opacity, 1)) !important
        }

        .link-success {
            color: RGBA(var(--bs-success-rgb), var(--bs-link-opacity, 1)) !important;
            -webkit-text-decoration-color: RGBA(var(--bs-success-rgb), var(--bs-link-underline-opacity, 1)) !important;
            text-decoration-color: RGBA(var(--bs-success-rgb), var(--bs-link-underline-opacity, 1)) !important
        }

        .link-success:focus,
        .link-success:hover {
            color: RGBA(20, 108, 67, var(--bs-link-opacity, 1)) !important;
            -webkit-text-decoration-color: RGBA(20, 108, 67, var(--bs-link-underline-opacity, 1)) !important;
            text-decoration-color: RGBA(20, 108, 67, var(--bs-link-underline-opacity, 1)) !important
        }

        .link-info {
            color: RGBA(var(--bs-info-rgb), var(--bs-link-opacity, 1)) !important;
            -webkit-text-decoration-color: RGBA(var(--bs-info-rgb), var(--bs-link-underline-opacity, 1)) !important;
            text-decoration-color: RGBA(var(--bs-info-rgb), var(--bs-link-underline-opacity, 1)) !important
        }

        .link-info:focus,
        .link-info:hover {
            color: RGBA(61, 213, 243, var(--bs-link-opacity, 1)) !important;
            -webkit-text-decoration-color: RGBA(61, 213, 243, var(--bs-link-underline-opacity, 1)) !important;
            text-decoration-color: RGBA(61, 213, 243, var(--bs-link-underline-opacity, 1)) !important
        }

        .link-warning {
            color: RGBA(var(--bs-warning-rgb), var(--bs-link-opacity, 1)) !important;
            -webkit-text-decoration-color: RGBA(var(--bs-warning-rgb), var(--bs-link-underline-opacity, 1)) !important;
            text-decoration-color: RGBA(var(--bs-warning-rgb), var(--bs-link-underline-opacity, 1)) !important
        }

        .link-warning:focus,
        .link-warning:hover {
            color: RGBA(255, 205, 57, var(--bs-link-opacity, 1)) !important;
            -webkit-text-decoration-color: RGBA(255, 205, 57, var(--bs-link-underline-opacity, 1)) !important;
            text-decoration-color: RGBA(255, 205, 57, var(--bs-link-underline-opacity, 1)) !important
        }

        .link-danger {
            color: RGBA(var(--bs-danger-rgb), var(--bs-link-opacity, 1)) !important;
            -webkit-text-decoration-color: RGBA(var(--bs-danger-rgb), var(--bs-link-underline-opacity, 1)) !important;
            text-decoration-color: RGBA(var(--bs-danger-rgb), var(--bs-link-underline-opacity, 1)) !important
        }

        .link-danger:focus,
        .link-danger:hover {
            color: RGBA(176, 42, 55, var(--bs-link-opacity, 1)) !important;
            -webkit-text-decoration-color: RGBA(176, 42, 55, var(--bs-link-underline-opacity, 1)) !important;
            text-decoration-color: RGBA(176, 42, 55, var(--bs-link-underline-opacity, 1)) !important
        }

        .link-light {
            color: RGBA(var(--bs-light-rgb), var(--bs-link-opacity, 1)) !important;
            -webkit-text-decoration-color: RGBA(var(--bs-light-rgb), var(--bs-link-underline-opacity, 1)) !important;
            text-decoration-color: RGBA(var(--bs-light-rgb), var(--bs-link-underline-opacity, 1)) !important
        }

        .link-light:focus,
        .link-light:hover {
            color: RGBA(249, 250, 251, var(--bs-link-opacity, 1)) !important;
            -webkit-text-decoration-color: RGBA(249, 250, 251, var(--bs-link-underline-opacity, 1)) !important;
            text-decoration-color: RGBA(249, 250, 251, var(--bs-link-underline-opacity, 1)) !important
        }

        .link-dark {
            color: RGBA(var(--bs-dark-rgb), var(--bs-link-opacity, 1)) !important;
            -webkit-text-decoration-color: RGBA(var(--bs-dark-rgb), var(--bs-link-underline-opacity, 1)) !important;
            text-decoration-color: RGBA(var(--bs-dark-rgb), var(--bs-link-underline-opacity, 1)) !important
        }

        .link-dark:focus,
        .link-dark:hover {
            color: RGBA(26, 30, 33, var(--bs-link-opacity, 1)) !important;
            -webkit-text-decoration-color: RGBA(26, 30, 33, var(--bs-link-underline-opacity, 1)) !important;
            text-decoration-color: RGBA(26, 30, 33, var(--bs-link-underline-opacity, 1)) !important
        }

        .link-body-emphasis {
            color: RGBA(var(--bs-emphasis-color-rgb), var(--bs-link-opacity, 1)) !important;
            -webkit-text-decoration-color: RGBA(var(--bs-emphasis-color-rgb), var(--bs-link-underline-opacity, 1)) !important;
            text-decoration-color: RGBA(var(--bs-emphasis-color-rgb), var(--bs-link-underline-opacity, 1)) !important
        }

        .link-body-emphasis:focus,
        .link-body-emphasis:hover {
            color: RGBA(var(--bs-emphasis-color-rgb), var(--bs-link-opacity, .75)) !important;
            -webkit-text-decoration-color: RGBA(var(--bs-emphasis-color-rgb), var(--bs-link-underline-opacity, 0.75)) !important;
            text-decoration-color: RGBA(var(--bs-emphasis-color-rgb), var(--bs-link-underline-opacity, 0.75)) !important
        }

        .focus-ring:focus {
            outline: 0;
            box-shadow: var(--bs-focus-ring-x, 0) var(--bs-focus-ring-y, 0) var(--bs-focus-ring-blur, 0) var(--bs-focus-ring-width) var(--bs-focus-ring-color)
        }

        .icon-link {
            display: inline-flex;
            gap: .375rem;
            align-items: center;
            -webkit-text-decoration-color: rgba(var(--bs-link-color-rgb), var(--bs-link-opacity, 0.5));
            text-decoration-color: rgba(var(--bs-link-color-rgb), var(--bs-link-opacity, 0.5));
            text-underline-offset: 0.25em;
            -webkit-backface-visibility: hidden;
            backface-visibility: hidden
        }

        .icon-link>.bi {
            flex-shrink: 0;
            width: 1em;
            height: 1em;
            fill: currentcolor;
            transition: .2s ease-in-out transform
        }

        @media (prefers-reduced-motion:reduce) {
            .icon-link>.bi {
                transition: none
            }
        }

        .icon-link-hover:focus-visible>.bi,
        .icon-link-hover:hover>.bi {
            transform: var(--bs-icon-link-transform, translate3d(.25em, 0, 0))
        }

        .ratio {
            position: relative;
            width: 100%
        }

        .ratio::before {
            display: block;
            padding-top: var(--bs-aspect-ratio);
            content: ""
        }

        .ratio>* {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%
        }

        .ratio-1x1 {
            --bs-aspect-ratio: 100%
        }

        .ratio-4x3 {
            --bs-aspect-ratio: 75%
        }

        .ratio-16x9 {
            --bs-aspect-ratio: 56.25%
        }

        .ratio-21x9 {
            --bs-aspect-ratio: 42.8571428571%
        }

        .fixed-top {

            top: 0;
            right: 0;
            left: 0;
            z-index: 1030
        }

        .fixed-bottom {
            position: fixed;
            right: 0;
            bottom: 0;
            left: 0;
            z-index: 1030
        }

        .sticky-top {
            position: -webkit-sticky;
            position: sticky;
            top: 0;
            z-index: 1020
        }

        .sticky-bottom {
            position: -webkit-sticky;
            position: sticky;
            bottom: 0;
            z-index: 1020
        }

        @media (min-width:576px) {
            .sticky-sm-top {
                position: -webkit-sticky;
                position: sticky;
                top: 0;
                z-index: 1020
            }

            .sticky-sm-bottom {
                position: -webkit-sticky;
                position: sticky;
                bottom: 0;
                z-index: 1020
            }
        }

        @media (min-width:768px) {
            .sticky-md-top {
                position: -webkit-sticky;
                position: sticky;
                top: 0;
                z-index: 1020
            }

            .sticky-md-bottom {
                position: -webkit-sticky;
                position: sticky;
                bottom: 0;
                z-index: 1020
            }
        }

        @media (min-width:992px) {
            .sticky-lg-top {
                position: -webkit-sticky;
                position: sticky;
                top: 0;
                z-index: 1020
            }

            .sticky-lg-bottom {
                position: -webkit-sticky;
                position: sticky;
                bottom: 0;
                z-index: 1020
            }
        }

        @media (min-width:1200px) {
            .sticky-xl-top {
                position: -webkit-sticky;
                position: sticky;
                top: 0;
                z-index: 1020
            }

            .sticky-xl-bottom {
                position: -webkit-sticky;
                position: sticky;
                bottom: 0;
                z-index: 1020
            }
        }

        @media (min-width:1400px) {
            .sticky-xxl-top {
                position: -webkit-sticky;
                position: sticky;
                top: 0;
                z-index: 1020
            }

            .sticky-xxl-bottom {
                position: -webkit-sticky;
                position: sticky;
                bottom: 0;
                z-index: 1020
            }
        }

        .hstack {
            display: flex;
            flex-direction: row;
            align-items: center;
            align-self: stretch
        }

        .vstack {
            display: flex;
            flex: 1 1 auto;
            flex-direction: column;
            align-self: stretch
        }

        .visually-hidden,
        .visually-hidden-focusable:not(:focus):not(:focus-within) {
            width: 1px !important;
            height: 1px !important;
            padding: 0 !important;
            margin: -1px !important;
            overflow: hidden !important;
            clip: rect(0, 0, 0, 0) !important;
            white-space: nowrap !important;
            border: 0 !important
        }

        .visually-hidden-focusable:not(:focus):not(:focus-within):not(caption),
        .visually-hidden:not(caption) {
            position: absolute !important
        }

        .stretched-link::after {
            position: absolute;
            top: 0;
            right: 0;
            bottom: 0;
            left: 0;
            z-index: 1;
            content: ""
        }

        .text-truncate {
            overflow: hidden;
            text-overflow: ellipsis;
            white-space: nowrap
        }

        .vr {
            display: inline-block;
            align-self: stretch;
            width: 1px;
            min-height: 1em;
            background-color: currentcolor;
            opacity: .25
        }

        .align-baseline {
            vertical-align: baseline !important
        }

        .align-top {
            vertical-align: top !important
        }

        .align-middle {
            vertical-align: middle !important
        }

        .align-bottom {
            vertical-align: bottom !important
        }

        .align-text-bottom {
            vertical-align: text-bottom !important
        }

        .align-text-top {
            vertical-align: text-top !important
        }

        .float-start {
            float: left !important
        }

        .float-end {
            float: right !important
        }

        .float-none {
            float: none !important
        }

        .object-fit-contain {
            -o-object-fit: contain !important;
            object-fit: contain !important
        }

        .object-fit-cover {
            -o-object-fit: cover !important;
            object-fit: cover !important
        }

        .object-fit-fill {
            -o-object-fit: fill !important;
            object-fit: fill !important
        }

        .object-fit-scale {
            -o-object-fit: scale-down !important;
            object-fit: scale-down !important
        }

        .object-fit-none {
            -o-object-fit: none !important;
            object-fit: none !important
        }

        .opacity-0 {
            opacity: 0 !important
        }

        .opacity-25 {
            opacity: .25 !important
        }

        .opacity-50 {
            opacity: .5 !important
        }

        .opacity-75 {
            opacity: .75 !important
        }

        .opacity-100 {
            opacity: 1 !important
        }

        .overflow-auto {
            overflow: auto !important
        }

        .overflow-hidden {
            overflow: hidden !important
        }

        .overflow-visible {
            overflow: visible !important
        }

        .overflow-scroll {
            overflow: scroll !important
        }

        .overflow-x-auto {
            overflow-x: auto !important
        }

        .overflow-x-hidden {
            overflow-x: hidden !important
        }

        .overflow-x-visible {
            overflow-x: visible !important
        }

        .overflow-x-scroll {
            overflow-x: scroll !important
        }

        .overflow-y-auto {
            overflow-y: auto !important
        }

        .overflow-y-hidden {
            overflow-y: hidden !important
        }

        .overflow-y-visible {
            overflow-y: visible !important
        }

        .overflow-y-scroll {
            overflow-y: scroll !important
        }

        .d-inline {
            display: inline !important
        }

        .d-inline-block {
            display: inline-block !important
        }

        .d-block {
            display: block !important
        }

        .d-grid {
            display: grid !important
        }

        .d-inline-grid {
            display: inline-grid !important
        }

        .d-table {
            display: table !important
        }

        .d-table-row {
            display: table-row !important
        }

        .d-table-cell {
            display: table-cell !important
        }

        .d-flex {
            display: flex !important
        }

        .d-inline-flex {
            display: inline-flex !important
        }

        .d-none {
            display: none !important
        }

        .shadow {
            box-shadow: 0 .5rem 1rem rgba(0, 0, 0, .15) !important
        }

        .shadow-sm {
            box-shadow: 0 .125rem .25rem rgba(0, 0, 0, .075) !important
        }

        .shadow-lg {
            box-shadow: 0 1rem 3rem rgba(0, 0, 0, .175) !important
        }

        .shadow-none {
            box-shadow: none !important
        }

        .focus-ring-primary {
            --bs-focus-ring-color: rgba(var(--bs-primary-rgb), var(--bs-focus-ring-opacity))
        }

        .focus-ring-secondary {
            --bs-focus-ring-color: rgba(var(--bs-secondary-rgb), var(--bs-focus-ring-opacity))
        }

        .focus-ring-success {
            --bs-focus-ring-color: rgba(var(--bs-success-rgb), var(--bs-focus-ring-opacity))
        }

        .focus-ring-info {
            --bs-focus-ring-color: rgba(var(--bs-info-rgb), var(--bs-focus-ring-opacity))
        }

        .focus-ring-warning {
            --bs-focus-ring-color: rgba(var(--bs-warning-rgb), var(--bs-focus-ring-opacity))
        }

        .focus-ring-danger {
            --bs-focus-ring-color: rgba(var(--bs-danger-rgb), var(--bs-focus-ring-opacity))
        }

        .focus-ring-light {
            --bs-focus-ring-color: rgba(var(--bs-light-rgb), var(--bs-focus-ring-opacity))
        }

        .focus-ring-dark {
            --bs-focus-ring-color: rgba(var(--bs-dark-rgb), var(--bs-focus-ring-opacity))
        }

        .position-static {
            position: static !important
        }

        .position-relative {
            position: relative !important
        }

        .position-absolute {
            position: absolute !important
        }

        .position-fixed {
            position: fixed !important
        }

        .position-sticky {
            position: -webkit-sticky !important;
            position: sticky !important
        }

        .top-0 {
            top: 0 !important
        }

        .top-50 {
            top: 50% !important
        }

        .top-100 {
            top: 100% !important
        }

        .bottom-0 {
            bottom: 0 !important
        }

        .bottom-50 {
            bottom: 50% !important
        }

        .bottom-100 {
            bottom: 100% !important
        }

        .start-0 {
            left: 0 !important
        }

        .start-50 {
            left: 50% !important
        }

        .start-100 {
            left: 100% !important
        }

        .end-0 {
            right: 0 !important
        }

        .end-50 {
            right: 50% !important
        }

        .end-100 {
            right: 100% !important
        }

        .translate-middle {
            transform: translate(-50%, -50%) !important
        }

        .translate-middle-x {
            transform: translateX(-50%) !important
        }

        .translate-middle-y {
            transform: translateY(-50%) !important
        }

        .border {
            border: var(--bs-border-width) var(--bs-border-style) var(--bs-border-color) !important
        }

        .border-0 {
            border: 0 !important
        }

        .border-top {
            border-top: var(--bs-border-width) var(--bs-border-style) var(--bs-border-color) !important
        }

        .border-top-0 {
            border-top: 0 !important
        }

        .border-end {
            border-right: var(--bs-border-width) var(--bs-border-style) var(--bs-border-color) !important
        }

        .border-end-0 {
            border-right: 0 !important
        }

        .border-bottom {
            border-bottom: var(--bs-border-width) var(--bs-border-style) var(--bs-border-color) !important
        }

        .border-bottom-0 {
            border-bottom: 0 !important
        }

        .border-start {
            border-left: var(--bs-border-width) var(--bs-border-style) var(--bs-border-color) !important
        }

        .border-start-0 {
            border-left: 0 !important
        }

        .border-primary {
            --bs-border-opacity: 1;
            border-color: rgba(var(--bs-primary-rgb), var(--bs-border-opacity)) !important
        }

        .border-secondary {
            --bs-border-opacity: 1;
            border-color: rgba(var(--bs-secondary-rgb), var(--bs-border-opacity)) !important
        }

        .border-success {
            --bs-border-opacity: 1;
            border-color: rgba(var(--bs-success-rgb), var(--bs-border-opacity)) !important
        }

        .border-info {
            --bs-border-opacity: 1;
            border-color: rgba(var(--bs-info-rgb), var(--bs-border-opacity)) !important
        }

        .border-warning {
            --bs-border-opacity: 1;
            border-color: rgba(var(--bs-warning-rgb), var(--bs-border-opacity)) !important
        }

        .border-danger {
            --bs-border-opacity: 1;
            border-color: rgba(var(--bs-danger-rgb), var(--bs-border-opacity)) !important
        }

        .border-light {
            --bs-border-opacity: 1;
            border-color: rgba(var(--bs-light-rgb), var(--bs-border-opacity)) !important
        }

        .border-dark {
            --bs-border-opacity: 1;
            border-color: rgba(var(--bs-dark-rgb), var(--bs-border-opacity)) !important
        }

        .border-black {
            --bs-border-opacity: 1;
            border-color: rgba(var(--bs-black-rgb), var(--bs-border-opacity)) !important
        }

        .border-white {
            --bs-border-opacity: 1;
            border-color: rgba(var(--bs-white-rgb), var(--bs-border-opacity)) !important
        }

        .border-primary-subtle {
            border-color: var(--bs-primary-border-subtle) !important
        }

        .border-secondary-subtle {
            border-color: var(--bs-secondary-border-subtle) !important
        }

        .border-success-subtle {
            border-color: var(--bs-success-border-subtle) !important
        }

        .border-info-subtle {
            border-color: var(--bs-info-border-subtle) !important
        }

        .border-warning-subtle {
            border-color: var(--bs-warning-border-subtle) !important
        }

        .border-danger-subtle {
            border-color: var(--bs-danger-border-subtle) !important
        }

        .border-light-subtle {
            border-color: var(--bs-light-border-subtle) !important
        }

        .border-dark-subtle {
            border-color: var(--bs-dark-border-subtle) !important
        }

        .border-1 {
            border-width: 1px !important
        }

        .border-2 {
            border-width: 2px !important
        }

        .border-3 {
            border-width: 3px !important
        }

        .border-4 {
            border-width: 4px !important
        }

        .border-5 {
            border-width: 5px !important
        }

        .border-opacity-10 {
            --bs-border-opacity: 0.1
        }

        .border-opacity-25 {
            --bs-border-opacity: 0.25
        }

        .border-opacity-50 {
            --bs-border-opacity: 0.5
        }

        .border-opacity-75 {
            --bs-border-opacity: 0.75
        }

        .border-opacity-100 {
            --bs-border-opacity: 1
        }

        .w-25 {
            width: 25% !important
        }

        .w-50 {
            width: 50% !important
        }

        .w-75 {
            width: 75% !important
        }

        .w-100 {
            width: 100% !important
        }

        .w-auto {
            width: auto !important
        }

        .mw-100 {
            max-width: 100% !important
        }

        .vw-100 {
            width: 100vw !important
        }

        .min-vw-100 {
            min-width: 100vw !important
        }

        .h-25 {
            height: 25% !important
        }

        .h-50 {
            height: 50% !important
        }

        .h-75 {
            height: 75% !important
        }

        .h-100 {
            height: 100% !important
        }

        .h-auto {
            height: auto !important
        }

        .mh-100 {
            max-height: 100% !important
        }

        .vh-100 {
            height: 100vh !important
        }

        .min-vh-100 {
            min-height: 100vh !important
        }

        .flex-fill {
            flex: 1 1 auto !important
        }

        .flex-row {
            flex-direction: row !important
        }

        .flex-column {
            flex-direction: column !important
        }

        .flex-row-reverse {
            flex-direction: row-reverse !important
        }

        .flex-column-reverse {
            flex-direction: column-reverse !important
        }

        .flex-grow-0 {
            flex-grow: 0 !important
        }

        .flex-grow-1 {
            flex-grow: 1 !important
        }

        .flex-shrink-0 {
            flex-shrink: 0 !important
        }

        .flex-shrink-1 {
            flex-shrink: 1 !important
        }

        .flex-wrap {
            flex-wrap: wrap !important
        }

        .flex-nowrap {
            flex-wrap: nowrap !important
        }

        .flex-wrap-reverse {
            flex-wrap: wrap-reverse !important
        }

        .justify-content-start {
            justify-content: flex-start !important
        }

        .justify-content-end {
            justify-content: flex-end !important
        }

        .justify-content-center {
            justify-content: center !important
        }

        .justify-content-between {
            justify-content: space-between !important
        }

        .justify-content-around {
            justify-content: space-around !important
        }

        .justify-content-evenly {
            justify-content: space-evenly !important
        }

        .align-items-start {
            align-items: flex-start !important
        }

        .align-items-end {
            align-items: flex-end !important
        }

        .align-items-center {
            align-items: center !important
        }

        .align-items-baseline {
            align-items: baseline !important
        }

        .align-items-stretch {
            align-items: stretch !important
        }

        .align-content-start {
            align-content: flex-start !important
        }

        .align-content-end {
            align-content: flex-end !important
        }

        .align-content-center {
            align-content: center !important
        }

        .align-content-between {
            align-content: space-between !important
        }

        .align-content-around {
            align-content: space-around !important
        }

        .align-content-stretch {
            align-content: stretch !important
        }

        .align-self-auto {
            align-self: auto !important
        }

        .align-self-start {
            align-self: flex-start !important
        }

        .align-self-end {
            align-self: flex-end !important
        }

        .align-self-center {
            align-self: center !important
        }

        .align-self-baseline {
            align-self: baseline !important
        }

        .align-self-stretch {
            align-self: stretch !important
        }

        .order-first {
            order: -1 !important
        }

        .order-0 {
            order: 0 !important
        }

        .order-1 {
            order: 1 !important
        }

        .order-2 {
            order: 2 !important
        }

        .order-3 {
            order: 3 !important
        }

        .order-4 {
            order: 4 !important
        }

        .order-5 {
            order: 5 !important
        }

        .order-last {
            order: 6 !important
        }

        .m-0 {
            margin: 0 !important
        }

        .m-1 {
            margin: .25rem !important
        }

        .m-2 {
            margin: .5rem !important
        }

        .m-3 {
            margin: 1rem !important
        }

        .m-4 {
            margin: 1.5rem !important
        }

        .m-5 {
            margin: 3rem !important
        }

        .m-auto {
            margin: auto !important
        }

        .mx-0 {
            margin-right: 0 !important;
            margin-left: 0 !important
        }

        .mx-1 {
            margin-right: .25rem !important;
            margin-left: .25rem !important
        }

        .mx-2 {
            margin-right: .5rem !important;
            margin-left: .5rem !important
        }

        .mx-3 {
            margin-right: 1rem !important;
            margin-left: 1rem !important
        }

        .mx-4 {
            margin-right: 1.5rem !important;
            margin-left: 1.5rem !important
        }

        .mx-5 {
            margin-right: 3rem !important;
            margin-left: 3rem !important
        }

        .mx-auto {
            margin-right: auto !important;
            margin-left: auto !important
        }

        .my-0 {
            margin-top: 0 !important;
            margin-bottom: 0 !important
        }

        .my-1 {
            margin-top: .25rem !important;
            margin-bottom: .25rem !important
        }

        .my-2 {
            margin-top: .5rem !important;
            margin-bottom: .5rem !important
        }

        .my-3 {
            margin-top: 1rem !important;
            margin-bottom: 1rem !important
        }

        .my-4 {
            margin-top: 1.5rem !important;
            margin-bottom: 1.5rem !important
        }

        .my-5 {
            margin-top: 3rem !important;
            margin-bottom: 3rem !important
        }

        .my-auto {
            margin-top: auto !important;
            margin-bottom: auto !important
        }

        .mt-0 {
            margin-top: 0 !important
        }

        .mt-1 {
            margin-top: .25rem !important
        }

        .mt-2 {
            margin-top: .5rem !important
        }

        .mt-3 {
            margin-top: 1rem !important
        }

        .mt-4 {
            margin-top: 1.5rem !important
        }

        .mt-5 {
            margin-top: 3rem !important
        }

        .mt-auto {
            margin-top: auto !important
        }

        .me-0 {
            margin-right: 0 !important
        }

        .me-1 {
            margin-right: .25rem !important
        }

        .me-2 {
            margin-right: .5rem !important
        }

        .me-3 {
            margin-right: 1rem !important
        }

        .me-4 {
            margin-right: 1.5rem !important
        }

        .me-5 {
            margin-right: 3rem !important
        }

        .me-auto {
            margin-right: auto !important
        }

        .mb-0 {
            margin-bottom: 0 !important
        }

        .mb-1 {
            margin-bottom: .25rem !important
        }

        .mb-2 {
            margin-bottom: .5rem !important
        }

        .mb-3 {
            margin-bottom: 1rem !important
        }

        .mb-4 {
            margin-bottom: 1.5rem !important
        }

        .mb-5 {
            margin-bottom: 3rem !important
        }

        .mb-auto {
            margin-bottom: auto !important
        }

        .ms-0 {
            margin-left: 0 !important
        }

        .ms-1 {
            margin-left: .25rem !important
        }

        .ms-2 {
            margin-left: .5rem !important
        }

        .ms-3 {
            margin-left: 1rem !important
        }

        .ms-4 {
            margin-left: 1.5rem !important
        }

        .ms-5 {
            margin-left: 3rem !important
        }

        .ms-auto {
            margin-left: auto !important
        }

        .p-0 {
            padding: 0 !important
        }

        .p-1 {
            padding: .25rem !important
        }

        .p-2 {
            padding: .5rem !important
        }

        .p-3 {
            padding: 1rem !important
        }

        .p-4 {
            padding: 1.5rem !important
        }

        .p-5 {
            padding: 3rem !important
        }

        .px-0 {
            padding-right: 0 !important;
            padding-left: 0 !important
        }

        .px-1 {
            padding-right: .25rem !important;
            padding-left: .25rem !important
        }

        .px-2 {
            padding-right: .5rem !important;
            padding-left: .5rem !important
        }

        .px-3 {
            padding-right: 1rem !important;
            padding-left: 1rem !important
        }

        .px-4 {
            padding-right: 1.5rem !important;
            padding-left: 1.5rem !important
        }

        .px-5 {
            padding-right: 3rem !important;
            padding-left: 3rem !important
        }

        .py-0 {
            padding-top: 0 !important;
            padding-bottom: 0 !important
        }

        .py-1 {
            padding-top: .25rem !important;
            padding-bottom: .25rem !important
        }

        .py-2 {
            padding-top: .5rem !important;
            padding-bottom: .5rem !important
        }

        .py-3 {
            padding-top: 1rem !important;
            padding-bottom: 1rem !important
        }

        .py-4 {
            padding-top: 1.5rem !important;
            padding-bottom: 1.5rem !important
        }

        .py-5 {
            padding-top: 3rem !important;
            padding-bottom: 3rem !important
        }

        .pt-0 {
            padding-top: 0 !important
        }

        .pt-1 {
            padding-top: .25rem !important
        }

        .pt-2 {
            padding-top: .5rem !important
        }

        .pt-3 {
            padding-top: 1rem !important
        }

        .pt-4 {
            padding-top: 1.5rem !important
        }

        .pt-5 {
            padding-top: 3rem !important
        }

        .pe-0 {
            padding-right: 0 !important
        }

        .pe-1 {
            padding-right: .25rem !important
        }

        .pe-2 {
            padding-right: .5rem !important
        }

        .pe-3 {
            padding-right: 1rem !important
        }

        .pe-4 {
            padding-right: 1.5rem !important
        }

        .pe-5 {
            padding-right: 3rem !important
        }

        .pb-0 {
            padding-bottom: 0 !important
        }

        .pb-1 {
            padding-bottom: .25rem !important
        }

        .pb-2 {
            padding-bottom: .5rem !important
        }

        .pb-3 {
            padding-bottom: 1rem !important
        }

        .pb-4 {
            padding-bottom: 1.5rem !important
        }

        .pb-5 {
            padding-bottom: 3rem !important
        }

        .ps-0 {
            padding-left: 0 !important
        }

        .ps-1 {
            padding-left: .25rem !important
        }

        .ps-2 {
            padding-left: .5rem !important
        }

        .ps-3 {
            padding-left: 1rem !important
        }

        .ps-4 {
            padding-left: 1.5rem !important
        }

        .ps-5 {
            padding-left: 3rem !important
        }

        .gap-0 {
            gap: 0 !important
        }

        .gap-1 {
            gap: .25rem !important
        }

        .gap-2 {
            gap: .5rem !important
        }

        .gap-3 {
            gap: 1rem !important
        }

        .gap-4 {
            gap: 1.5rem !important
        }

        .gap-5 {
            gap: 3rem !important
        }

        .row-gap-0 {
            row-gap: 0 !important
        }

        .row-gap-1 {
            row-gap: .25rem !important
        }

        .row-gap-2 {
            row-gap: .5rem !important
        }

        .row-gap-3 {
            row-gap: 1rem !important
        }

        .row-gap-4 {
            row-gap: 1.5rem !important
        }

        .row-gap-5 {
            row-gap: 3rem !important
        }

        .column-gap-0 {
            -moz-column-gap: 0 !important;
            column-gap: 0 !important
        }

        .column-gap-1 {
            -moz-column-gap: 0.25rem !important;
            column-gap: .25rem !important
        }

        .column-gap-2 {
            -moz-column-gap: 0.5rem !important;
            column-gap: .5rem !important
        }

        .column-gap-3 {
            -moz-column-gap: 1rem !important;
            column-gap: 1rem !important
        }

        .column-gap-4 {
            -moz-column-gap: 1.5rem !important;
            column-gap: 1.5rem !important
        }

        .column-gap-5 {
            -moz-column-gap: 3rem !important;
            column-gap: 3rem !important
        }

        .font-monospace {
            font-family: var(--bs-font-monospace) !important
        }

        .fs-1 {
            font-size: calc(1.375rem + 1.5vw) !important
        }

        .fs-2 {
            font-size: calc(1.325rem + .9vw) !important
        }

        .fs-3 {
            font-size: calc(1.3rem + .6vw) !important
        }

        .fs-4 {
            font-size: calc(1.275rem + .3vw) !important
        }

        .fs-5 {
            font-size: 1.25rem !important
        }

        .fs-6 {
            font-size: 1rem !important
        }

        .fst-italic {
            font-style: italic !important
        }

        .fst-normal {
            font-style: normal !important
        }

        .fw-lighter {
            font-weight: lighter !important
        }

        .fw-light {
            font-weight: 300 !important
        }

        .fw-normal {
            font-weight: 400 !important
        }

        .fw-medium {
            font-weight: 500 !important
        }

        .fw-semibold {
            font-weight: 600 !important
        }

        .fw-bold {
            font-weight: 700 !important
        }

        .fw-bolder {
            font-weight: bolder !important
        }

        .lh-1 {
            line-height: 1 !important
        }

        .lh-sm {
            line-height: 1.25 !important
        }

        .lh-base {
            line-height: 1.5 !important
        }

        .lh-lg {
            line-height: 2 !important
        }

        .text-start {
            text-align: left !important
        }

        .text-end {
            text-align: right !important
        }

        .text-center {
            text-align: center !important
        }

        .text-decoration-none {
            text-decoration: none !important
        }

        .text-decoration-underline {
            text-decoration: underline !important
        }

        .text-decoration-line-through {
            text-decoration: line-through !important
        }

        .text-lowercase {
            text-transform: lowercase !important
        }

        .text-uppercase {
            text-transform: uppercase !important
        }

        .text-capitalize {
            text-transform: capitalize !important
        }

        .text-wrap {
            white-space: normal !important
        }

        .text-nowrap {
            white-space: nowrap !important
        }

        .text-break {
            word-wrap: break-word !important;
            word-break: break-word !important
        }

        .text-primary {
            --bs-text-opacity: 1;
            color: rgba(var(--bs-primary-rgb), var(--bs-text-opacity)) !important
        }

        .text-secondary {
            --bs-text-opacity: 1;
            color: rgba(var(--bs-secondary-rgb), var(--bs-text-opacity)) !important
        }

        .text-success {
            --bs-text-opacity: 1;
            color: rgba(var(--bs-success-rgb), var(--bs-text-opacity)) !important
        }

        .text-info {
            --bs-text-opacity: 1;
            color: rgba(var(--bs-info-rgb), var(--bs-text-opacity)) !important
        }

        .text-warning {
            --bs-text-opacity: 1;
            color: rgba(var(--bs-warning-rgb), var(--bs-text-opacity)) !important
        }

        .text-danger {
            --bs-text-opacity: 1;
            color: rgba(var(--bs-danger-rgb), var(--bs-text-opacity)) !important
        }

        .text-light {
            --bs-text-opacity: 1;
            color: rgba(var(--bs-light-rgb), var(--bs-text-opacity)) !important
        }

        .text-dark {
            --bs-text-opacity: 1;
            color: rgba(var(--bs-dark-rgb), var(--bs-text-opacity)) !important
        }

        .text-black {
            --bs-text-opacity: 1;
            color: rgba(var(--bs-black-rgb), var(--bs-text-opacity)) !important
        }

        .text-white {
            --bs-text-opacity: 1;
            color: rgba(var(--bs-white-rgb), var(--bs-text-opacity)) !important
        }

        .text-body {
            --bs-text-opacity: 1;
            color: rgba(var(--bs-body-color-rgb), var(--bs-text-opacity)) !important
        }

        .text-muted {
            --bs-text-opacity: 1;
            color: var(--bs-secondary-color) !important
        }

        .text-black-50 {
            --bs-text-opacity: 1;
            color: rgba(0, 0, 0, .5) !important
        }

        .text-white-50 {
            --bs-text-opacity: 1;
            color: rgba(255, 255, 255, .5) !important
        }

        .text-body-secondary {
            --bs-text-opacity: 1;
            color: var(--bs-secondary-color) !important
        }

        .text-body-tertiary {
            --bs-text-opacity: 1;
            color: var(--bs-tertiary-color) !important
        }

        .text-body-emphasis {
            --bs-text-opacity: 1;
            color: var(--bs-emphasis-color) !important
        }

        .text-reset {
            --bs-text-opacity: 1;
            color: inherit !important
        }

        .text-opacity-25 {
            --bs-text-opacity: 0.25
        }

        .text-opacity-50 {
            --bs-text-opacity: 0.5
        }

        .text-opacity-75 {
            --bs-text-opacity: 0.75
        }

        .text-opacity-100 {
            --bs-text-opacity: 1
        }

        .text-primary-emphasis {
            color: var(--bs-primary-text-emphasis) !important
        }

        .text-secondary-emphasis {
            color: var(--bs-secondary-text-emphasis) !important
        }

        .text-success-emphasis {
            color: var(--bs-success-text-emphasis) !important
        }

        .text-info-emphasis {
            color: var(--bs-info-text-emphasis) !important
        }

        .text-warning-emphasis {
            color: var(--bs-warning-text-emphasis) !important
        }

        .text-danger-emphasis {
            color: var(--bs-danger-text-emphasis) !important
        }

        .text-light-emphasis {
            color: var(--bs-light-text-emphasis) !important
        }

        .text-dark-emphasis {
            color: var(--bs-dark-text-emphasis) !important
        }

        .link-opacity-10 {
            --bs-link-opacity: 0.1
        }

        .link-opacity-10-hover:hover {
            --bs-link-opacity: 0.1
        }

        .link-opacity-25 {
            --bs-link-opacity: 0.25
        }

        .link-opacity-25-hover:hover {
            --bs-link-opacity: 0.25
        }

        .link-opacity-50 {
            --bs-link-opacity: 0.5
        }

        .link-opacity-50-hover:hover {
            --bs-link-opacity: 0.5
        }

        .link-opacity-75 {
            --bs-link-opacity: 0.75
        }

        .link-opacity-75-hover:hover {
            --bs-link-opacity: 0.75
        }

        .link-opacity-100 {
            --bs-link-opacity: 1
        }

        .link-opacity-100-hover:hover {
            --bs-link-opacity: 1
        }

        .link-offset-1 {
            text-underline-offset: 0.125em !important
        }

        .link-offset-1-hover:hover {
            text-underline-offset: 0.125em !important
        }

        .link-offset-2 {
            text-underline-offset: 0.25em !important
        }

        .link-offset-2-hover:hover {
            text-underline-offset: 0.25em !important
        }

        .link-offset-3 {
            text-underline-offset: 0.375em !important
        }

        .link-offset-3-hover:hover {
            text-underline-offset: 0.375em !important
        }

        .link-underline-primary {
            --bs-link-underline-opacity: 1;
            -webkit-text-decoration-color: rgba(var(--bs-primary-rgb), var(--bs-link-underline-opacity)) !important;
            text-decoration-color: rgba(var(--bs-primary-rgb), var(--bs-link-underline-opacity)) !important
        }

        .link-underline-secondary {
            --bs-link-underline-opacity: 1;
            -webkit-text-decoration-color: rgba(var(--bs-secondary-rgb), var(--bs-link-underline-opacity)) !important;
            text-decoration-color: rgba(var(--bs-secondary-rgb), var(--bs-link-underline-opacity)) !important
        }

        .link-underline-success {
            --bs-link-underline-opacity: 1;
            -webkit-text-decoration-color: rgba(var(--bs-success-rgb), var(--bs-link-underline-opacity)) !important;
            text-decoration-color: rgba(var(--bs-success-rgb), var(--bs-link-underline-opacity)) !important
        }

        .link-underline-info {
            --bs-link-underline-opacity: 1;
            -webkit-text-decoration-color: rgba(var(--bs-info-rgb), var(--bs-link-underline-opacity)) !important;
            text-decoration-color: rgba(var(--bs-info-rgb), var(--bs-link-underline-opacity)) !important
        }

        .link-underline-warning {
            --bs-link-underline-opacity: 1;
            -webkit-text-decoration-color: rgba(var(--bs-warning-rgb), var(--bs-link-underline-opacity)) !important;
            text-decoration-color: rgba(var(--bs-warning-rgb), var(--bs-link-underline-opacity)) !important
        }

        .link-underline-danger {
            --bs-link-underline-opacity: 1;
            -webkit-text-decoration-color: rgba(var(--bs-danger-rgb), var(--bs-link-underline-opacity)) !important;
            text-decoration-color: rgba(var(--bs-danger-rgb), var(--bs-link-underline-opacity)) !important
        }

        .link-underline-light {
            --bs-link-underline-opacity: 1;
            -webkit-text-decoration-color: rgba(var(--bs-light-rgb), var(--bs-link-underline-opacity)) !important;
            text-decoration-color: rgba(var(--bs-light-rgb), var(--bs-link-underline-opacity)) !important
        }

        .link-underline-dark {
            --bs-link-underline-opacity: 1;
            -webkit-text-decoration-color: rgba(var(--bs-dark-rgb), var(--bs-link-underline-opacity)) !important;
            text-decoration-color: rgba(var(--bs-dark-rgb), var(--bs-link-underline-opacity)) !important
        }

        .link-underline {
            --bs-link-underline-opacity: 1;
            -webkit-text-decoration-color: rgba(var(--bs-link-color-rgb), var(--bs-link-underline-opacity, 1)) !important;
            text-decoration-color: rgba(var(--bs-link-color-rgb), var(--bs-link-underline-opacity, 1)) !important
        }

        .link-underline-opacity-0 {
            --bs-link-underline-opacity: 0
        }

        .link-underline-opacity-0-hover:hover {
            --bs-link-underline-opacity: 0
        }

        .link-underline-opacity-10 {
            --bs-link-underline-opacity: 0.1
        }

        .link-underline-opacity-10-hover:hover {
            --bs-link-underline-opacity: 0.1
        }

        .link-underline-opacity-25 {
            --bs-link-underline-opacity: 0.25
        }

        .link-underline-opacity-25-hover:hover {
            --bs-link-underline-opacity: 0.25
        }

        .link-underline-opacity-50 {
            --bs-link-underline-opacity: 0.5
        }

        .link-underline-opacity-50-hover:hover {
            --bs-link-underline-opacity: 0.5
        }

        .link-underline-opacity-75 {
            --bs-link-underline-opacity: 0.75
        }

        .link-underline-opacity-75-hover:hover {
            --bs-link-underline-opacity: 0.75
        }

        .link-underline-opacity-100 {
            --bs-link-underline-opacity: 1
        }

        .link-underline-opacity-100-hover:hover {
            --bs-link-underline-opacity: 1
        }

        .bg-primary {
            --bs-bg-opacity: 1;
            background-color: rgba(var(--bs-primary-rgb), var(--bs-bg-opacity)) !important
        }

        .bg-secondary {
            --bs-bg-opacity: 1;
            background-color: rgba(var(--bs-secondary-rgb), var(--bs-bg-opacity)) !important
        }

        .bg-success {
            --bs-bg-opacity: 1;
            background-color: rgba(var(--bs-success-rgb), var(--bs-bg-opacity)) !important
        }

        .bg-info {
            --bs-bg-opacity: 1;
            background-color: rgba(var(--bs-info-rgb), var(--bs-bg-opacity)) !important
        }

        .bg-warning {
            --bs-bg-opacity: 1;
            background-color: rgba(var(--bs-warning-rgb), var(--bs-bg-opacity)) !important
        }

        .bg-danger {
            --bs-bg-opacity: 1;
            background-color: rgba(var(--bs-danger-rgb), var(--bs-bg-opacity)) !important
        }

        .bg-light {
            --bs-bg-opacity: 1;
            background-color: rgba(var(--bs-light-rgb), var(--bs-bg-opacity)) !important
        }

        .bg-dark {
            --bs-bg-opacity: 1;
            background-color: rgba(var(--bs-dark-rgb), var(--bs-bg-opacity)) !important
        }

        .bg-black {
            --bs-bg-opacity: 1;
            background-color: rgba(var(--bs-black-rgb), var(--bs-bg-opacity)) !important
        }

        .bg-white {
            --bs-bg-opacity: 1;
            background-color: rgba(var(--bs-white-rgb), var(--bs-bg-opacity)) !important
        }

        .bg-body {
            --bs-bg-opacity: 1;
            background-color: rgba(var(--bs-body-bg-rgb), var(--bs-bg-opacity)) !important
        }

        .bg-transparent {
            --bs-bg-opacity: 1;
            background-color: transparent !important
        }

        .bg-body-secondary {
            --bs-bg-opacity: 1;
            background-color: rgba(var(--bs-secondary-bg-rgb), var(--bs-bg-opacity)) !important
        }

        .bg-body-tertiary {
            --bs-bg-opacity: 1;
            background-color: rgba(var(--bs-tertiary-bg-rgb), var(--bs-bg-opacity)) !important
        }

        .bg-opacity-10 {
            --bs-bg-opacity: 0.1
        }

        .bg-opacity-25 {
            --bs-bg-opacity: 0.25
        }

        .bg-opacity-50 {
            --bs-bg-opacity: 0.5
        }

        .bg-opacity-75 {
            --bs-bg-opacity: 0.75
        }

        .bg-opacity-100 {
            --bs-bg-opacity: 1
        }

        .bg-primary-subtle {
            background-color: var(--bs-primary-bg-subtle) !important
        }

        .bg-secondary-subtle {
            background-color: var(--bs-secondary-bg-subtle) !important
        }

        .bg-success-subtle {
            background-color: var(--bs-success-bg-subtle) !important
        }

        .bg-info-subtle {
            background-color: var(--bs-info-bg-subtle) !important
        }

        .bg-warning-subtle {
            background-color: var(--bs-warning-bg-subtle) !important
        }

        .bg-danger-subtle {
            background-color: var(--bs-danger-bg-subtle) !important
        }

        .bg-light-subtle {
            background-color: var(--bs-light-bg-subtle) !important
        }

        .bg-dark-subtle {
            background-color: var(--bs-dark-bg-subtle) !important
        }

        .bg-gradient {
            background-image: var(--bs-gradient) !important
        }

        .user-select-all {
            -webkit-user-select: all !important;
            -moz-user-select: all !important;
            user-select: all !important
        }

        .user-select-auto {
            -webkit-user-select: auto !important;
            -moz-user-select: auto !important;
            user-select: auto !important
        }

        .user-select-none {
            -webkit-user-select: none !important;
            -moz-user-select: none !important;
            user-select: none !important
        }

        .pe-none {
            pointer-events: none !important
        }

        .pe-auto {
            pointer-events: auto !important
        }

        .rounded {
            border-radius: var(--bs-border-radius) !important
        }

        .rounded-0 {
            border-radius: 0 !important
        }

        .rounded-1 {
            border-radius: var(--bs-border-radius-sm) !important
        }

        .rounded-2 {
            border-radius: var(--bs-border-radius) !important
        }

        .rounded-3 {
            border-radius: var(--bs-border-radius-lg) !important
        }

        .rounded-4 {
            border-radius: var(--bs-border-radius-xl) !important
        }

        .rounded-5 {
            border-radius: var(--bs-border-radius-xxl) !important
        }

        .rounded-circle {
            border-radius: 50% !important
        }

        .rounded-pill {
            border-radius: var(--bs-border-radius-pill) !important
        }

        .rounded-top {
            border-top-left-radius: var(--bs-border-radius) !important;
            border-top-right-radius: var(--bs-border-radius) !important
        }

        .rounded-top-0 {
            border-top-left-radius: 0 !important;
            border-top-right-radius: 0 !important
        }

        .rounded-top-1 {
            border-top-left-radius: var(--bs-border-radius-sm) !important;
            border-top-right-radius: var(--bs-border-radius-sm) !important
        }

        .rounded-top-2 {
            border-top-left-radius: var(--bs-border-radius) !important;
            border-top-right-radius: var(--bs-border-radius) !important
        }

        .rounded-top-3 {
            border-top-left-radius: var(--bs-border-radius-lg) !important;
            border-top-right-radius: var(--bs-border-radius-lg) !important
        }

        .rounded-top-4 {
            border-top-left-radius: var(--bs-border-radius-xl) !important;
            border-top-right-radius: var(--bs-border-radius-xl) !important
        }

        .rounded-top-5 {
            border-top-left-radius: var(--bs-border-radius-xxl) !important;
            border-top-right-radius: var(--bs-border-radius-xxl) !important
        }

        .rounded-top-circle {
            border-top-left-radius: 50% !important;
            border-top-right-radius: 50% !important
        }

        .rounded-top-pill {
            border-top-left-radius: var(--bs-border-radius-pill) !important;
            border-top-right-radius: var(--bs-border-radius-pill) !important
        }

        .rounded-end {
            border-top-right-radius: var(--bs-border-radius) !important;
            border-bottom-right-radius: var(--bs-border-radius) !important
        }

        .rounded-end-0 {
            border-top-right-radius: 0 !important;
            border-bottom-right-radius: 0 !important
        }

        .rounded-end-1 {
            border-top-right-radius: var(--bs-border-radius-sm) !important;
            border-bottom-right-radius: var(--bs-border-radius-sm) !important
        }

        .rounded-end-2 {
            border-top-right-radius: var(--bs-border-radius) !important;
            border-bottom-right-radius: var(--bs-border-radius) !important
        }

        .rounded-end-3 {
            border-top-right-radius: var(--bs-border-radius-lg) !important;
            border-bottom-right-radius: var(--bs-border-radius-lg) !important
        }

        .rounded-end-4 {
            border-top-right-radius: var(--bs-border-radius-xl) !important;
            border-bottom-right-radius: var(--bs-border-radius-xl) !important
        }

        .rounded-end-5 {
            border-top-right-radius: var(--bs-border-radius-xxl) !important;
            border-bottom-right-radius: var(--bs-border-radius-xxl) !important
        }

        .rounded-end-circle {
            border-top-right-radius: 50% !important;
            border-bottom-right-radius: 50% !important
        }

        .rounded-end-pill {
            border-top-right-radius: var(--bs-border-radius-pill) !important;
            border-bottom-right-radius: var(--bs-border-radius-pill) !important
        }

        .rounded-bottom {
            border-bottom-right-radius: var(--bs-border-radius) !important;
            border-bottom-left-radius: var(--bs-border-radius) !important
        }

        .rounded-bottom-0 {
            border-bottom-right-radius: 0 !important;
            border-bottom-left-radius: 0 !important
        }

        .rounded-bottom-1 {
            border-bottom-right-radius: var(--bs-border-radius-sm) !important;
            border-bottom-left-radius: var(--bs-border-radius-sm) !important
        }

        .rounded-bottom-2 {
            border-bottom-right-radius: var(--bs-border-radius) !important;
            border-bottom-left-radius: var(--bs-border-radius) !important
        }

        .rounded-bottom-3 {
            border-bottom-right-radius: var(--bs-border-radius-lg) !important;
            border-bottom-left-radius: var(--bs-border-radius-lg) !important
        }

        .rounded-bottom-4 {
            border-bottom-right-radius: var(--bs-border-radius-xl) !important;
            border-bottom-left-radius: var(--bs-border-radius-xl) !important
        }

        .rounded-bottom-5 {
            border-bottom-right-radius: var(--bs-border-radius-xxl) !important;
            border-bottom-left-radius: var(--bs-border-radius-xxl) !important
        }

        .rounded-bottom-circle {
            border-bottom-right-radius: 50% !important;
            border-bottom-left-radius: 50% !important
        }

        .rounded-bottom-pill {
            border-bottom-right-radius: var(--bs-border-radius-pill) !important;
            border-bottom-left-radius: var(--bs-border-radius-pill) !important
        }

        .rounded-start {
            border-bottom-left-radius: var(--bs-border-radius) !important;
            border-top-left-radius: var(--bs-border-radius) !important
        }

        .rounded-start-0 {
            border-bottom-left-radius: 0 !important;
            border-top-left-radius: 0 !important
        }

        .rounded-start-1 {
            border-bottom-left-radius: var(--bs-border-radius-sm) !important;
            border-top-left-radius: var(--bs-border-radius-sm) !important
        }

        .rounded-start-2 {
            border-bottom-left-radius: var(--bs-border-radius) !important;
            border-top-left-radius: var(--bs-border-radius) !important
        }

        .rounded-start-3 {
            border-bottom-left-radius: var(--bs-border-radius-lg) !important;
            border-top-left-radius: var(--bs-border-radius-lg) !important
        }

        .rounded-start-4 {
            border-bottom-left-radius: var(--bs-border-radius-xl) !important;
            border-top-left-radius: var(--bs-border-radius-xl) !important
        }

        .rounded-start-5 {
            border-bottom-left-radius: var(--bs-border-radius-xxl) !important;
            border-top-left-radius: var(--bs-border-radius-xxl) !important
        }

        .rounded-start-circle {
            border-bottom-left-radius: 50% !important;
            border-top-left-radius: 50% !important
        }

        .rounded-start-pill {
            border-bottom-left-radius: var(--bs-border-radius-pill) !important;
            border-top-left-radius: var(--bs-border-radius-pill) !important
        }

        .visible {
            visibility: visible !important
        }

        .invisible {
            visibility: hidden !important
        }

        .z-n1 {
            z-index: -1 !important
        }

        .z-0 {
            z-index: 0 !important
        }

        .z-1 {
            z-index: 1 !important
        }

        .z-2 {
            z-index: 2 !important
        }

        .z-3 {
            z-index: 3 !important
        }

        @media (min-width:576px) {
            .float-sm-start {
                float: left !important
            }

            .float-sm-end {
                float: right !important
            }

            .float-sm-none {
                float: none !important
            }

            .object-fit-sm-contain {
                -o-object-fit: contain !important;
                object-fit: contain !important
            }

            .object-fit-sm-cover {
                -o-object-fit: cover !important;
                object-fit: cover !important
            }

            .object-fit-sm-fill {
                -o-object-fit: fill !important;
                object-fit: fill !important
            }

            .object-fit-sm-scale {
                -o-object-fit: scale-down !important;
                object-fit: scale-down !important
            }

            .object-fit-sm-none {
                -o-object-fit: none !important;
                object-fit: none !important
            }

            .d-sm-inline {
                display: inline !important
            }

            .d-sm-inline-block {
                display: inline-block !important
            }

            .d-sm-block {
                display: block !important
            }

            .d-sm-grid {
                display: grid !important
            }

            .d-sm-inline-grid {
                display: inline-grid !important
            }

            .d-sm-table {
                display: table !important
            }

            .d-sm-table-row {
                display: table-row !important
            }

            .d-sm-table-cell {
                display: table-cell !important
            }

            .d-sm-flex {
                display: flex !important
            }

            .d-sm-inline-flex {
                display: inline-flex !important
            }

            .d-sm-none {
                display: none !important
            }

            .flex-sm-fill {
                flex: 1 1 auto !important
            }

            .flex-sm-row {
                flex-direction: row !important
            }

            .flex-sm-column {
                flex-direction: column !important
            }

            .flex-sm-row-reverse {
                flex-direction: row-reverse !important
            }

            .flex-sm-column-reverse {
                flex-direction: column-reverse !important
            }

            .flex-sm-grow-0 {
                flex-grow: 0 !important
            }

            .flex-sm-grow-1 {
                flex-grow: 1 !important
            }

            .flex-sm-shrink-0 {
                flex-shrink: 0 !important
            }

            .flex-sm-shrink-1 {
                flex-shrink: 1 !important
            }

            .flex-sm-wrap {
                flex-wrap: wrap !important
            }

            .flex-sm-nowrap {
                flex-wrap: nowrap !important
            }

            .flex-sm-wrap-reverse {
                flex-wrap: wrap-reverse !important
            }

            .justify-content-sm-start {
                justify-content: flex-start !important
            }

            .justify-content-sm-end {
                justify-content: flex-end !important
            }

            .justify-content-sm-center {
                justify-content: center !important
            }

            .justify-content-sm-between {
                justify-content: space-between !important
            }

            .justify-content-sm-around {
                justify-content: space-around !important
            }

            .justify-content-sm-evenly {
                justify-content: space-evenly !important
            }

            .align-items-sm-start {
                align-items: flex-start !important
            }

            .align-items-sm-end {
                align-items: flex-end !important
            }

            .align-items-sm-center {
                align-items: center !important
            }

            .align-items-sm-baseline {
                align-items: baseline !important
            }

            .align-items-sm-stretch {
                align-items: stretch !important
            }

            .align-content-sm-start {
                align-content: flex-start !important
            }

            .align-content-sm-end {
                align-content: flex-end !important
            }

            .align-content-sm-center {
                align-content: center !important
            }

            .align-content-sm-between {
                align-content: space-between !important
            }

            .align-content-sm-around {
                align-content: space-around !important
            }

            .align-content-sm-stretch {
                align-content: stretch !important
            }

            .align-self-sm-auto {
                align-self: auto !important
            }

            .align-self-sm-start {
                align-self: flex-start !important
            }

            .align-self-sm-end {
                align-self: flex-end !important
            }

            .align-self-sm-center {
                align-self: center !important
            }

            .align-self-sm-baseline {
                align-self: baseline !important
            }

            .align-self-sm-stretch {
                align-self: stretch !important
            }

            .order-sm-first {
                order: -1 !important
            }

            .order-sm-0 {
                order: 0 !important
            }

            .order-sm-1 {
                order: 1 !important
            }

            .order-sm-2 {
                order: 2 !important
            }

            .order-sm-3 {
                order: 3 !important
            }

            .order-sm-4 {
                order: 4 !important
            }

            .order-sm-5 {
                order: 5 !important
            }

            .order-sm-last {
                order: 6 !important
            }

            .m-sm-0 {
                margin: 0 !important
            }

            .m-sm-1 {
                margin: .25rem !important
            }

            .m-sm-2 {
                margin: .5rem !important
            }

            .m-sm-3 {
                margin: 1rem !important
            }

            .m-sm-4 {
                margin: 1.5rem !important
            }

            .m-sm-5 {
                margin: 3rem !important
            }

            .m-sm-auto {
                margin: auto !important
            }

            .mx-sm-0 {
                margin-right: 0 !important;
                margin-left: 0 !important
            }

            .mx-sm-1 {
                margin-right: .25rem !important;
                margin-left: .25rem !important
            }

            .mx-sm-2 {
                margin-right: .5rem !important;
                margin-left: .5rem !important
            }

            .mx-sm-3 {
                margin-right: 1rem !important;
                margin-left: 1rem !important
            }

            .mx-sm-4 {
                margin-right: 1.5rem !important;
                margin-left: 1.5rem !important
            }

            .mx-sm-5 {
                margin-right: 3rem !important;
                margin-left: 3rem !important
            }

            .mx-sm-auto {
                margin-right: auto !important;
                margin-left: auto !important
            }

            .my-sm-0 {
                margin-top: 0 !important;
                margin-bottom: 0 !important
            }

            .my-sm-1 {
                margin-top: .25rem !important;
                margin-bottom: .25rem !important
            }

            .my-sm-2 {
                margin-top: .5rem !important;
                margin-bottom: .5rem !important
            }

            .my-sm-3 {
                margin-top: 1rem !important;
                margin-bottom: 1rem !important
            }

            .my-sm-4 {
                margin-top: 1.5rem !important;
                margin-bottom: 1.5rem !important
            }

            .my-sm-5 {
                margin-top: 3rem !important;
                margin-bottom: 3rem !important
            }

            .my-sm-auto {
                margin-top: auto !important;
                margin-bottom: auto !important
            }

            .mt-sm-0 {
                margin-top: 0 !important
            }

            .mt-sm-1 {
                margin-top: .25rem !important
            }

            .mt-sm-2 {
                margin-top: .5rem !important
            }

            .mt-sm-3 {
                margin-top: 1rem !important
            }

            .mt-sm-4 {
                margin-top: 1.5rem !important
            }

            .mt-sm-5 {
                margin-top: 3rem !important
            }

            .mt-sm-auto {
                margin-top: auto !important
            }

            .me-sm-0 {
                margin-right: 0 !important
            }

            .me-sm-1 {
                margin-right: .25rem !important
            }

            .me-sm-2 {
                margin-right: .5rem !important
            }

            .me-sm-3 {
                margin-right: 1rem !important
            }

            .me-sm-4 {
                margin-right: 1.5rem !important
            }

            .me-sm-5 {
                margin-right: 3rem !important
            }

            .me-sm-auto {
                margin-right: auto !important
            }

            .mb-sm-0 {
                margin-bottom: 0 !important
            }

            .mb-sm-1 {
                margin-bottom: .25rem !important
            }

            .mb-sm-2 {
                margin-bottom: .5rem !important
            }

            .mb-sm-3 {
                margin-bottom: 1rem !important
            }

            .mb-sm-4 {
                margin-bottom: 1.5rem !important
            }

            .mb-sm-5 {
                margin-bottom: 3rem !important
            }

            .mb-sm-auto {
                margin-bottom: auto !important
            }

            .ms-sm-0 {
                margin-left: 0 !important
            }

            .ms-sm-1 {
                margin-left: .25rem !important
            }

            .ms-sm-2 {
                margin-left: .5rem !important
            }

            .ms-sm-3 {
                margin-left: 1rem !important
            }

            .ms-sm-4 {
                margin-left: 1.5rem !important
            }

            .ms-sm-5 {
                margin-left: 3rem !important
            }

            .ms-sm-auto {
                margin-left: auto !important
            }

            .p-sm-0 {
                padding: 0 !important
            }

            .p-sm-1 {
                padding: .25rem !important
            }

            .p-sm-2 {
                padding: .5rem !important
            }

            .p-sm-3 {
                padding: 1rem !important
            }

            .p-sm-4 {
                padding: 1.5rem !important
            }

            .p-sm-5 {
                padding: 3rem !important
            }

            .px-sm-0 {
                padding-right: 0 !important;
                padding-left: 0 !important
            }

            .px-sm-1 {
                padding-right: .25rem !important;
                padding-left: .25rem !important
            }

            .px-sm-2 {
                padding-right: .5rem !important;
                padding-left: .5rem !important
            }

            .px-sm-3 {
                padding-right: 1rem !important;
                padding-left: 1rem !important
            }

            .px-sm-4 {
                padding-right: 1.5rem !important;
                padding-left: 1.5rem !important
            }

            .px-sm-5 {
                padding-right: 3rem !important;
                padding-left: 3rem !important
            }

            .py-sm-0 {
                padding-top: 0 !important;
                padding-bottom: 0 !important
            }

            .py-sm-1 {
                padding-top: .25rem !important;
                padding-bottom: .25rem !important
            }

            .py-sm-2 {
                padding-top: .5rem !important;
                padding-bottom: .5rem !important
            }

            .py-sm-3 {
                padding-top: 1rem !important;
                padding-bottom: 1rem !important
            }

            .py-sm-4 {
                padding-top: 1.5rem !important;
                padding-bottom: 1.5rem !important
            }

            .py-sm-5 {
                padding-top: 3rem !important;
                padding-bottom: 3rem !important
            }

            .pt-sm-0 {
                padding-top: 0 !important
            }

            .pt-sm-1 {
                padding-top: .25rem !important
            }

            .pt-sm-2 {
                padding-top: .5rem !important
            }

            .pt-sm-3 {
                padding-top: 1rem !important
            }

            .pt-sm-4 {
                padding-top: 1.5rem !important
            }

            .pt-sm-5 {
                padding-top: 3rem !important
            }

            .pe-sm-0 {
                padding-right: 0 !important
            }

            .pe-sm-1 {
                padding-right: .25rem !important
            }

            .pe-sm-2 {
                padding-right: .5rem !important
            }

            .pe-sm-3 {
                padding-right: 1rem !important
            }

            .pe-sm-4 {
                padding-right: 1.5rem !important
            }

            .pe-sm-5 {
                padding-right: 3rem !important
            }

            .pb-sm-0 {
                padding-bottom: 0 !important
            }

            .pb-sm-1 {
                padding-bottom: .25rem !important
            }

            .pb-sm-2 {
                padding-bottom: .5rem !important
            }

            .pb-sm-3 {
                padding-bottom: 1rem !important
            }

            .pb-sm-4 {
                padding-bottom: 1.5rem !important
            }

            .pb-sm-5 {
                padding-bottom: 3rem !important
            }

            .ps-sm-0 {
                padding-left: 0 !important
            }

            .ps-sm-1 {
                padding-left: .25rem !important
            }

            .ps-sm-2 {
                padding-left: .5rem !important
            }

            .ps-sm-3 {
                padding-left: 1rem !important
            }

            .ps-sm-4 {
                padding-left: 1.5rem !important
            }

            .ps-sm-5 {
                padding-left: 3rem !important
            }

            .gap-sm-0 {
                gap: 0 !important
            }

            .gap-sm-1 {
                gap: .25rem !important
            }

            .gap-sm-2 {
                gap: .5rem !important
            }

            .gap-sm-3 {
                gap: 1rem !important
            }

            .gap-sm-4 {
                gap: 1.5rem !important
            }

            .gap-sm-5 {
                gap: 3rem !important
            }

            .row-gap-sm-0 {
                row-gap: 0 !important
            }

            .row-gap-sm-1 {
                row-gap: .25rem !important
            }

            .row-gap-sm-2 {
                row-gap: .5rem !important
            }

            .row-gap-sm-3 {
                row-gap: 1rem !important
            }

            .row-gap-sm-4 {
                row-gap: 1.5rem !important
            }

            .row-gap-sm-5 {
                row-gap: 3rem !important
            }

            .column-gap-sm-0 {
                -moz-column-gap: 0 !important;
                column-gap: 0 !important
            }

            .column-gap-sm-1 {
                -moz-column-gap: 0.25rem !important;
                column-gap: .25rem !important
            }

            .column-gap-sm-2 {
                -moz-column-gap: 0.5rem !important;
                column-gap: .5rem !important
            }

            .column-gap-sm-3 {
                -moz-column-gap: 1rem !important;
                column-gap: 1rem !important
            }

            .column-gap-sm-4 {
                -moz-column-gap: 1.5rem !important;
                column-gap: 1.5rem !important
            }

            .column-gap-sm-5 {
                -moz-column-gap: 3rem !important;
                column-gap: 3rem !important
            }

            .text-sm-start {
                text-align: left !important
            }

            .text-sm-end {
                text-align: right !important
            }

            .text-sm-center {
                text-align: center !important
            }
        }

        @media (min-width:768px) {
            .float-md-start {
                float: left !important
            }

            .float-md-end {
                float: right !important
            }

            .float-md-none {
                float: none !important
            }

            .object-fit-md-contain {
                -o-object-fit: contain !important;
                object-fit: contain !important
            }

            .object-fit-md-cover {
                -o-object-fit: cover !important;
                object-fit: cover !important
            }

            .object-fit-md-fill {
                -o-object-fit: fill !important;
                object-fit: fill !important
            }

            .object-fit-md-scale {
                -o-object-fit: scale-down !important;
                object-fit: scale-down !important
            }

            .object-fit-md-none {
                -o-object-fit: none !important;
                object-fit: none !important
            }

            .d-md-inline {
                display: inline !important
            }

            .d-md-inline-block {
                display: inline-block !important
            }

            .d-md-block {
                display: block !important
            }

            .d-md-grid {
                display: grid !important
            }

            .d-md-inline-grid {
                display: inline-grid !important
            }

            .d-md-table {
                display: table !important
            }

            .d-md-table-row {
                display: table-row !important
            }

            .d-md-table-cell {
                display: table-cell !important
            }

            .d-md-flex {
                display: flex !important
            }

            .d-md-inline-flex {
                display: inline-flex !important
            }

            .d-md-none {
                display: none !important
            }

            .flex-md-fill {
                flex: 1 1 auto !important
            }

            .flex-md-row {
                flex-direction: row !important
            }

            .flex-md-column {
                flex-direction: column !important
            }

            .flex-md-row-reverse {
                flex-direction: row-reverse !important
            }

            .flex-md-column-reverse {
                flex-direction: column-reverse !important
            }

            .flex-md-grow-0 {
                flex-grow: 0 !important
            }

            .flex-md-grow-1 {
                flex-grow: 1 !important
            }

            .flex-md-shrink-0 {
                flex-shrink: 0 !important
            }

            .flex-md-shrink-1 {
                flex-shrink: 1 !important
            }

            .flex-md-wrap {
                flex-wrap: wrap !important
            }

            .flex-md-nowrap {
                flex-wrap: nowrap !important
            }

            .flex-md-wrap-reverse {
                flex-wrap: wrap-reverse !important
            }

            .justify-content-md-start {
                justify-content: flex-start !important
            }

            .justify-content-md-end {
                justify-content: flex-end !important
            }

            .justify-content-md-center {
                justify-content: center !important
            }

            .justify-content-md-between {
                justify-content: space-between !important
            }

            .justify-content-md-around {
                justify-content: space-around !important
            }

            .justify-content-md-evenly {
                justify-content: space-evenly !important
            }

            .align-items-md-start {
                align-items: flex-start !important
            }

            .align-items-md-end {
                align-items: flex-end !important
            }

            .align-items-md-center {
                align-items: center !important
            }

            .align-items-md-baseline {
                align-items: baseline !important
            }

            .align-items-md-stretch {
                align-items: stretch !important
            }

            .align-content-md-start {
                align-content: flex-start !important
            }

            .align-content-md-end {
                align-content: flex-end !important
            }

            .align-content-md-center {
                align-content: center !important
            }

            .align-content-md-between {
                align-content: space-between !important
            }

            .align-content-md-around {
                align-content: space-around !important
            }

            .align-content-md-stretch {
                align-content: stretch !important
            }

            .align-self-md-auto {
                align-self: auto !important
            }

            .align-self-md-start {
                align-self: flex-start !important
            }

            .align-self-md-end {
                align-self: flex-end !important
            }

            .align-self-md-center {
                align-self: center !important
            }

            .align-self-md-baseline {
                align-self: baseline !important
            }

            .align-self-md-stretch {
                align-self: stretch !important
            }

            .order-md-first {
                order: -1 !important
            }

            .order-md-0 {
                order: 0 !important
            }

            .order-md-1 {
                order: 1 !important
            }

            .order-md-2 {
                order: 2 !important
            }

            .order-md-3 {
                order: 3 !important
            }

            .order-md-4 {
                order: 4 !important
            }

            .order-md-5 {
                order: 5 !important
            }

            .order-md-last {
                order: 6 !important
            }

            .m-md-0 {
                margin: 0 !important
            }

            .m-md-1 {
                margin: .25rem !important
            }

            .m-md-2 {
                margin: .5rem !important
            }

            .m-md-3 {
                margin: 1rem !important
            }

            .m-md-4 {
                margin: 1.5rem !important
            }

            .m-md-5 {
                margin: 3rem !important
            }

            .m-md-auto {
                margin: auto !important
            }

            .mx-md-0 {
                margin-right: 0 !important;
                margin-left: 0 !important
            }

            .mx-md-1 {
                margin-right: .25rem !important;
                margin-left: .25rem !important
            }

            .mx-md-2 {
                margin-right: .5rem !important;
                margin-left: .5rem !important
            }

            .mx-md-3 {
                margin-right: 1rem !important;
                margin-left: 1rem !important
            }

            .mx-md-4 {
                margin-right: 1.5rem !important;
                margin-left: 1.5rem !important
            }

            .mx-md-5 {
                margin-right: 3rem !important;
                margin-left: 3rem !important
            }

            .mx-md-auto {
                margin-right: auto !important;
                margin-left: auto !important
            }

            .my-md-0 {
                margin-top: 0 !important;
                margin-bottom: 0 !important
            }

            .my-md-1 {
                margin-top: .25rem !important;
                margin-bottom: .25rem !important
            }

            .my-md-2 {
                margin-top: .5rem !important;
                margin-bottom: .5rem !important
            }

            .my-md-3 {
                margin-top: 1rem !important;
                margin-bottom: 1rem !important
            }

            .my-md-4 {
                margin-top: 1.5rem !important;
                margin-bottom: 1.5rem !important
            }

            .my-md-5 {
                margin-top: 3rem !important;
                margin-bottom: 3rem !important
            }

            .my-md-auto {
                margin-top: auto !important;
                margin-bottom: auto !important
            }

            .mt-md-0 {
                margin-top: 0 !important
            }

            .mt-md-1 {
                margin-top: .25rem !important
            }

            .mt-md-2 {
                margin-top: .5rem !important
            }

            .mt-md-3 {
                margin-top: 1rem !important
            }

            .mt-md-4 {
                margin-top: 1.5rem !important
            }

            .mt-md-5 {
                margin-top: 3rem !important
            }

            .mt-md-auto {
                margin-top: auto !important
            }

            .me-md-0 {
                margin-right: 0 !important
            }

            .me-md-1 {
                margin-right: .25rem !important
            }

            .me-md-2 {
                margin-right: .5rem !important
            }

            .me-md-3 {
                margin-right: 1rem !important
            }

            .me-md-4 {
                margin-right: 1.5rem !important
            }

            .me-md-5 {
                margin-right: 3rem !important
            }

            .me-md-auto {
                margin-right: auto !important
            }

            .mb-md-0 {
                margin-bottom: 0 !important
            }

            .mb-md-1 {
                margin-bottom: .25rem !important
            }

            .mb-md-2 {
                margin-bottom: .5rem !important
            }

            .mb-md-3 {
                margin-bottom: 1rem !important
            }

            .mb-md-4 {
                margin-bottom: 1.5rem !important
            }

            .mb-md-5 {
                margin-bottom: 3rem !important
            }

            .mb-md-auto {
                margin-bottom: auto !important
            }

            .ms-md-0 {
                margin-left: 0 !important
            }

            .ms-md-1 {
                margin-left: .25rem !important
            }

            .ms-md-2 {
                margin-left: .5rem !important
            }

            .ms-md-3 {
                margin-left: 1rem !important
            }

            .ms-md-4 {
                margin-left: 1.5rem !important
            }

            .ms-md-5 {
                margin-left: 3rem !important
            }

            .ms-md-auto {
                margin-left: auto !important
            }

            .p-md-0 {
                padding: 0 !important
            }

            .p-md-1 {
                padding: .25rem !important
            }

            .p-md-2 {
                padding: .5rem !important
            }

            .p-md-3 {
                padding: 1rem !important
            }

            .p-md-4 {
                padding: 1.5rem !important
            }

            .p-md-5 {
                padding: 3rem !important
            }

            .px-md-0 {
                padding-right: 0 !important;
                padding-left: 0 !important
            }

            .px-md-1 {
                padding-right: .25rem !important;
                padding-left: .25rem !important
            }

            .px-md-2 {
                padding-right: .5rem !important;
                padding-left: .5rem !important
            }

            .px-md-3 {
                padding-right: 1rem !important;
                padding-left: 1rem !important
            }

            .px-md-4 {
                padding-right: 1.5rem !important;
                padding-left: 1.5rem !important
            }

            .px-md-5 {
                padding-right: 3rem !important;
                padding-left: 3rem !important
            }

            .py-md-0 {
                padding-top: 0 !important;
                padding-bottom: 0 !important
            }

            .py-md-1 {
                padding-top: .25rem !important;
                padding-bottom: .25rem !important
            }

            .py-md-2 {
                padding-top: .5rem !important;
                padding-bottom: .5rem !important
            }

            .py-md-3 {
                padding-top: 1rem !important;
                padding-bottom: 1rem !important
            }

            .py-md-4 {
                padding-top: 1.5rem !important;
                padding-bottom: 1.5rem !important
            }

            .py-md-5 {
                padding-top: 3rem !important;
                padding-bottom: 3rem !important
            }

            .pt-md-0 {
                padding-top: 0 !important
            }

            .pt-md-1 {
                padding-top: .25rem !important
            }

            .pt-md-2 {
                padding-top: .5rem !important
            }

            .pt-md-3 {
                padding-top: 1rem !important
            }

            .pt-md-4 {
                padding-top: 1.5rem !important
            }

            .pt-md-5 {
                padding-top: 3rem !important
            }

            .pe-md-0 {
                padding-right: 0 !important
            }

            .pe-md-1 {
                padding-right: .25rem !important
            }

            .pe-md-2 {
                padding-right: .5rem !important
            }

            .pe-md-3 {
                padding-right: 1rem !important
            }

            .pe-md-4 {
                padding-right: 1.5rem !important
            }

            .pe-md-5 {
                padding-right: 3rem !important
            }

            .pb-md-0 {
                padding-bottom: 0 !important
            }

            .pb-md-1 {
                padding-bottom: .25rem !important
            }

            .pb-md-2 {
                padding-bottom: .5rem !important
            }

            .pb-md-3 {
                padding-bottom: 1rem !important
            }

            .pb-md-4 {
                padding-bottom: 1.5rem !important
            }

            .pb-md-5 {
                padding-bottom: 3rem !important
            }

            .ps-md-0 {
                padding-left: 0 !important
            }

            .ps-md-1 {
                padding-left: .25rem !important
            }

            .ps-md-2 {
                padding-left: .5rem !important
            }

            .ps-md-3 {
                padding-left: 1rem !important
            }

            .ps-md-4 {
                padding-left: 1.5rem !important
            }

            .ps-md-5 {
                padding-left: 3rem !important
            }

            .gap-md-0 {
                gap: 0 !important
            }

            .gap-md-1 {
                gap: .25rem !important
            }

            .gap-md-2 {
                gap: .5rem !important
            }

            .gap-md-3 {
                gap: 1rem !important
            }

            .gap-md-4 {
                gap: 1.5rem !important
            }

            .gap-md-5 {
                gap: 3rem !important
            }

            .row-gap-md-0 {
                row-gap: 0 !important
            }

            .row-gap-md-1 {
                row-gap: .25rem !important
            }

            .row-gap-md-2 {
                row-gap: .5rem !important
            }

            .row-gap-md-3 {
                row-gap: 1rem !important
            }

            .row-gap-md-4 {
                row-gap: 1.5rem !important
            }

            .row-gap-md-5 {
                row-gap: 3rem !important
            }

            .column-gap-md-0 {
                -moz-column-gap: 0 !important;
                column-gap: 0 !important
            }

            .column-gap-md-1 {
                -moz-column-gap: 0.25rem !important;
                column-gap: .25rem !important
            }

            .column-gap-md-2 {
                -moz-column-gap: 0.5rem !important;
                column-gap: .5rem !important
            }

            .column-gap-md-3 {
                -moz-column-gap: 1rem !important;
                column-gap: 1rem !important
            }

            .column-gap-md-4 {
                -moz-column-gap: 1.5rem !important;
                column-gap: 1.5rem !important
            }

            .column-gap-md-5 {
                -moz-column-gap: 3rem !important;
                column-gap: 3rem !important
            }

            .text-md-start {
                text-align: left !important
            }

            .text-md-end {
                text-align: right !important
            }

            .text-md-center {
                text-align: center !important
            }
        }

        @media (min-width:992px) {
            .float-lg-start {
                float: left !important
            }

            .float-lg-end {
                float: right !important
            }

            .float-lg-none {
                float: none !important
            }

            .object-fit-lg-contain {
                -o-object-fit: contain !important;
                object-fit: contain !important
            }

            .object-fit-lg-cover {
                -o-object-fit: cover !important;
                object-fit: cover !important
            }

            .object-fit-lg-fill {
                -o-object-fit: fill !important;
                object-fit: fill !important
            }

            .object-fit-lg-scale {
                -o-object-fit: scale-down !important;
                object-fit: scale-down !important
            }

            .object-fit-lg-none {
                -o-object-fit: none !important;
                object-fit: none !important
            }

            .d-lg-inline {
                display: inline !important
            }

            .d-lg-inline-block {
                display: inline-block !important
            }

            .d-lg-block {
                display: block !important
            }

            .d-lg-grid {
                display: grid !important
            }

            .d-lg-inline-grid {
                display: inline-grid !important
            }

            .d-lg-table {
                display: table !important
            }

            .d-lg-table-row {
                display: table-row !important
            }

            .d-lg-table-cell {
                display: table-cell !important
            }

            .d-lg-flex {
                display: flex !important
            }

            .d-lg-inline-flex {
                display: inline-flex !important
            }

            .d-lg-none {
                display: none !important
            }

            .flex-lg-fill {
                flex: 1 1 auto !important
            }

            .flex-lg-row {
                flex-direction: row !important
            }

            .flex-lg-column {
                flex-direction: column !important
            }

            .flex-lg-row-reverse {
                flex-direction: row-reverse !important
            }

            .flex-lg-column-reverse {
                flex-direction: column-reverse !important
            }

            .flex-lg-grow-0 {
                flex-grow: 0 !important
            }

            .flex-lg-grow-1 {
                flex-grow: 1 !important
            }

            .flex-lg-shrink-0 {
                flex-shrink: 0 !important
            }

            .flex-lg-shrink-1 {
                flex-shrink: 1 !important
            }

            .flex-lg-wrap {
                flex-wrap: wrap !important
            }

            .flex-lg-nowrap {
                flex-wrap: nowrap !important
            }

            .flex-lg-wrap-reverse {
                flex-wrap: wrap-reverse !important
            }

            .justify-content-lg-start {
                justify-content: flex-start !important
            }

            .justify-content-lg-end {
                justify-content: flex-end !important
            }

            .justify-content-lg-center {
                justify-content: center !important
            }

            .justify-content-lg-between {
                justify-content: space-between !important
            }

            .justify-content-lg-around {
                justify-content: space-around !important
            }

            .justify-content-lg-evenly {
                justify-content: space-evenly !important
            }

            .align-items-lg-start {
                align-items: flex-start !important
            }

            .align-items-lg-end {
                align-items: flex-end !important
            }

            .align-items-lg-center {
                align-items: center !important
            }

            .align-items-lg-baseline {
                align-items: baseline !important
            }

            .align-items-lg-stretch {
                align-items: stretch !important
            }

            .align-content-lg-start {
                align-content: flex-start !important
            }

            .align-content-lg-end {
                align-content: flex-end !important
            }

            .align-content-lg-center {
                align-content: center !important
            }

            .align-content-lg-between {
                align-content: space-between !important
            }

            .align-content-lg-around {
                align-content: space-around !important
            }

            .align-content-lg-stretch {
                align-content: stretch !important
            }

            .align-self-lg-auto {
                align-self: auto !important
            }

            .align-self-lg-start {
                align-self: flex-start !important
            }

            .align-self-lg-end {
                align-self: flex-end !important
            }

            .align-self-lg-center {
                align-self: center !important
            }

            .align-self-lg-baseline {
                align-self: baseline !important
            }

            .align-self-lg-stretch {
                align-self: stretch !important
            }

            .order-lg-first {
                order: -1 !important
            }

            .order-lg-0 {
                order: 0 !important
            }

            .order-lg-1 {
                order: 1 !important
            }

            .order-lg-2 {
                order: 2 !important
            }

            .order-lg-3 {
                order: 3 !important
            }

            .order-lg-4 {
                order: 4 !important
            }

            .order-lg-5 {
                order: 5 !important
            }

            .order-lg-last {
                order: 6 !important
            }

            .m-lg-0 {
                margin: 0 !important
            }

            .m-lg-1 {
                margin: .25rem !important
            }

            .m-lg-2 {
                margin: .5rem !important
            }

            .m-lg-3 {
                margin: 1rem !important
            }

            .m-lg-4 {
                margin: 1.5rem !important
            }

            .m-lg-5 {
                margin: 3rem !important
            }

            .m-lg-auto {
                margin: auto !important
            }

            .mx-lg-0 {
                margin-right: 0 !important;
                margin-left: 0 !important
            }

            .mx-lg-1 {
                margin-right: .25rem !important;
                margin-left: .25rem !important
            }

            .mx-lg-2 {
                margin-right: .5rem !important;
                margin-left: .5rem !important
            }

            .mx-lg-3 {
                margin-right: 1rem !important;
                margin-left: 1rem !important
            }

            .mx-lg-4 {
                margin-right: 1.5rem !important;
                margin-left: 1.5rem !important
            }

            .mx-lg-5 {
                margin-right: 3rem !important;
                margin-left: 3rem !important
            }

            .mx-lg-auto {
                margin-right: auto !important;
                margin-left: auto !important
            }

            .my-lg-0 {
                margin-top: 0 !important;
                margin-bottom: 0 !important
            }

            .my-lg-1 {
                margin-top: .25rem !important;
                margin-bottom: .25rem !important
            }

            .my-lg-2 {
                margin-top: .5rem !important;
                margin-bottom: .5rem !important
            }

            .my-lg-3 {
                margin-top: 1rem !important;
                margin-bottom: 1rem !important
            }

            .my-lg-4 {
                margin-top: 1.5rem !important;
                margin-bottom: 1.5rem !important
            }

            .my-lg-5 {
                margin-top: 3rem !important;
                margin-bottom: 3rem !important
            }

            .my-lg-auto {
                margin-top: auto !important;
                margin-bottom: auto !important
            }

            .mt-lg-0 {
                margin-top: 0 !important
            }

            .mt-lg-1 {
                margin-top: .25rem !important
            }

            .mt-lg-2 {
                margin-top: .5rem !important
            }

            .mt-lg-3 {
                margin-top: 1rem !important
            }

            .mt-lg-4 {
                margin-top: 1.5rem !important
            }

            .mt-lg-5 {
                margin-top: 3rem !important
            }

            .mt-lg-auto {
                margin-top: auto !important
            }

            .me-lg-0 {
                margin-right: 0 !important
            }

            .me-lg-1 {
                margin-right: .25rem !important
            }

            .me-lg-2 {
                margin-right: .5rem !important
            }

            .me-lg-3 {
                margin-right: 1rem !important
            }

            .me-lg-4 {
                margin-right: 1.5rem !important
            }

            .me-lg-5 {
                margin-right: 3rem !important
            }

            .me-lg-auto {
                margin-right: auto !important
            }

            .mb-lg-0 {
                margin-bottom: 0 !important
            }

            .mb-lg-1 {
                margin-bottom: .25rem !important
            }

            .mb-lg-2 {
                margin-bottom: .5rem !important
            }

            .mb-lg-3 {
                margin-bottom: 1rem !important
            }

            .mb-lg-4 {
                margin-bottom: 1.5rem !important
            }

            .mb-lg-5 {
                margin-bottom: 3rem !important
            }

            .mb-lg-auto {
                margin-bottom: auto !important
            }

            .ms-lg-0 {
                margin-left: 0 !important
            }

            .ms-lg-1 {
                margin-left: .25rem !important
            }

            .ms-lg-2 {
                margin-left: .5rem !important
            }

            .ms-lg-3 {
                margin-left: 1rem !important
            }

            .ms-lg-4 {
                margin-left: 1.5rem !important
            }

            .ms-lg-5 {
                margin-left: 3rem !important
            }

            .ms-lg-auto {
                margin-left: auto !important
            }

            .p-lg-0 {
                padding: 0 !important
            }

            .p-lg-1 {
                padding: .25rem !important
            }

            .p-lg-2 {
                padding: .5rem !important
            }

            .p-lg-3 {
                padding: 1rem !important
            }

            .p-lg-4 {
                padding: 1.5rem !important
            }

            .p-lg-5 {
                padding: 3rem !important
            }

            .px-lg-0 {
                padding-right: 0 !important;
                padding-left: 0 !important
            }

            .px-lg-1 {
                padding-right: .25rem !important;
                padding-left: .25rem !important
            }

            .px-lg-2 {
                padding-right: .5rem !important;
                padding-left: .5rem !important
            }

            .px-lg-3 {
                padding-right: 1rem !important;
                padding-left: 1rem !important
            }

            .px-lg-4 {
                padding-right: 1.5rem !important;
                padding-left: 1.5rem !important
            }

            .px-lg-5 {
                padding-right: 3rem !important;
                padding-left: 3rem !important
            }

            .py-lg-0 {
                padding-top: 0 !important;
                padding-bottom: 0 !important
            }

            .py-lg-1 {
                padding-top: .25rem !important;
                padding-bottom: .25rem !important
            }

            .py-lg-2 {
                padding-top: .5rem !important;
                padding-bottom: .5rem !important
            }

            .py-lg-3 {
                padding-top: 1rem !important;
                padding-bottom: 1rem !important
            }

            .py-lg-4 {
                padding-top: 1.5rem !important;
                padding-bottom: 1.5rem !important
            }

            .py-lg-5 {
                padding-top: 3rem !important;
                padding-bottom: 3rem !important
            }

            .pt-lg-0 {
                padding-top: 0 !important
            }

            .pt-lg-1 {
                padding-top: .25rem !important
            }

            .pt-lg-2 {
                padding-top: .5rem !important
            }

            .pt-lg-3 {
                padding-top: 1rem !important
            }

            .pt-lg-4 {
                padding-top: 1.5rem !important
            }

            .pt-lg-5 {
                padding-top: 3rem !important
            }

            .pe-lg-0 {
                padding-right: 0 !important
            }

            .pe-lg-1 {
                padding-right: .25rem !important
            }

            .pe-lg-2 {
                padding-right: .5rem !important
            }

            .pe-lg-3 {
                padding-right: 1rem !important
            }

            .pe-lg-4 {
                padding-right: 1.5rem !important
            }

            .pe-lg-5 {
                padding-right: 3rem !important
            }

            .pb-lg-0 {
                padding-bottom: 0 !important
            }

            .pb-lg-1 {
                padding-bottom: .25rem !important
            }

            .pb-lg-2 {
                padding-bottom: .5rem !important
            }

            .pb-lg-3 {
                padding-bottom: 1rem !important
            }

            .pb-lg-4 {
                padding-bottom: 1.5rem !important
            }

            .pb-lg-5 {
                padding-bottom: 3rem !important
            }

            .ps-lg-0 {
                padding-left: 0 !important
            }

            .ps-lg-1 {
                padding-left: .25rem !important
            }

            .ps-lg-2 {
                padding-left: .5rem !important
            }

            .ps-lg-3 {
                padding-left: 1rem !important
            }

            .ps-lg-4 {
                padding-left: 1.5rem !important
            }

            .ps-lg-5 {
                padding-left: 3rem !important
            }

            .gap-lg-0 {
                gap: 0 !important
            }

            .gap-lg-1 {
                gap: .25rem !important
            }

            .gap-lg-2 {
                gap: .5rem !important
            }

            .gap-lg-3 {
                gap: 1rem !important
            }

            .gap-lg-4 {
                gap: 1.5rem !important
            }

            .gap-lg-5 {
                gap: 3rem !important
            }

            .row-gap-lg-0 {
                row-gap: 0 !important
            }

            .row-gap-lg-1 {
                row-gap: .25rem !important
            }

            .row-gap-lg-2 {
                row-gap: .5rem !important
            }

            .row-gap-lg-3 {
                row-gap: 1rem !important
            }

            .row-gap-lg-4 {
                row-gap: 1.5rem !important
            }

            .row-gap-lg-5 {
                row-gap: 3rem !important
            }

            .column-gap-lg-0 {
                -moz-column-gap: 0 !important;
                column-gap: 0 !important
            }

            .column-gap-lg-1 {
                -moz-column-gap: 0.25rem !important;
                column-gap: .25rem !important
            }

            .column-gap-lg-2 {
                -moz-column-gap: 0.5rem !important;
                column-gap: .5rem !important
            }

            .column-gap-lg-3 {
                -moz-column-gap: 1rem !important;
                column-gap: 1rem !important
            }

            .column-gap-lg-4 {
                -moz-column-gap: 1.5rem !important;
                column-gap: 1.5rem !important
            }

            .column-gap-lg-5 {
                -moz-column-gap: 3rem !important;
                column-gap: 3rem !important
            }

            .text-lg-start {
                text-align: left !important
            }

            .text-lg-end {
                text-align: right !important
            }

            .text-lg-center {
                text-align: center !important
            }
        }

        @media (min-width:1200px) {
            .float-xl-start {
                float: left !important
            }

            .float-xl-end {
                float: right !important
            }

            .float-xl-none {
                float: none !important
            }

            .object-fit-xl-contain {
                -o-object-fit: contain !important;
                object-fit: contain !important
            }

            .object-fit-xl-cover {
                -o-object-fit: cover !important;
                object-fit: cover !important
            }

            .object-fit-xl-fill {
                -o-object-fit: fill !important;
                object-fit: fill !important
            }

            .object-fit-xl-scale {
                -o-object-fit: scale-down !important;
                object-fit: scale-down !important
            }

            .object-fit-xl-none {
                -o-object-fit: none !important;
                object-fit: none !important
            }

            .d-xl-inline {
                display: inline !important
            }

            .d-xl-inline-block {
                display: inline-block !important
            }

            .d-xl-block {
                display: block !important
            }

            .d-xl-grid {
                display: grid !important
            }

            .d-xl-inline-grid {
                display: inline-grid !important
            }

            .d-xl-table {
                display: table !important
            }

            .d-xl-table-row {
                display: table-row !important
            }

            .d-xl-table-cell {
                display: table-cell !important
            }

            .d-xl-flex {
                display: flex !important
            }

            .d-xl-inline-flex {
                display: inline-flex !important
            }

            .d-xl-none {
                display: none !important
            }

            .flex-xl-fill {
                flex: 1 1 auto !important
            }

            .flex-xl-row {
                flex-direction: row !important
            }

            .flex-xl-column {
                flex-direction: column !important
            }

            .flex-xl-row-reverse {
                flex-direction: row-reverse !important
            }

            .flex-xl-column-reverse {
                flex-direction: column-reverse !important
            }

            .flex-xl-grow-0 {
                flex-grow: 0 !important
            }

            .flex-xl-grow-1 {
                flex-grow: 1 !important
            }

            .flex-xl-shrink-0 {
                flex-shrink: 0 !important
            }

            .flex-xl-shrink-1 {
                flex-shrink: 1 !important
            }

            .flex-xl-wrap {
                flex-wrap: wrap !important
            }

            .flex-xl-nowrap {
                flex-wrap: nowrap !important
            }

            .flex-xl-wrap-reverse {
                flex-wrap: wrap-reverse !important
            }

            .justify-content-xl-start {
                justify-content: flex-start !important
            }

            .justify-content-xl-end {
                justify-content: flex-end !important
            }

            .justify-content-xl-center {
                justify-content: center !important
            }

            .justify-content-xl-between {
                justify-content: space-between !important
            }

            .justify-content-xl-around {
                justify-content: space-around !important
            }

            .justify-content-xl-evenly {
                justify-content: space-evenly !important
            }

            .align-items-xl-start {
                align-items: flex-start !important
            }

            .align-items-xl-end {
                align-items: flex-end !important
            }

            .align-items-xl-center {
                align-items: center !important
            }

            .align-items-xl-baseline {
                align-items: baseline !important
            }

            .align-items-xl-stretch {
                align-items: stretch !important
            }

            .align-content-xl-start {
                align-content: flex-start !important
            }

            .align-content-xl-end {
                align-content: flex-end !important
            }

            .align-content-xl-center {
                align-content: center !important
            }

            .align-content-xl-between {
                align-content: space-between !important
            }

            .align-content-xl-around {
                align-content: space-around !important
            }

            .align-content-xl-stretch {
                align-content: stretch !important
            }

            .align-self-xl-auto {
                align-self: auto !important
            }

            .align-self-xl-start {
                align-self: flex-start !important
            }

            .align-self-xl-end {
                align-self: flex-end !important
            }

            .align-self-xl-center {
                align-self: center !important
            }

            .align-self-xl-baseline {
                align-self: baseline !important
            }

            .align-self-xl-stretch {
                align-self: stretch !important
            }

            .order-xl-first {
                order: -1 !important
            }

            .order-xl-0 {
                order: 0 !important
            }

            .order-xl-1 {
                order: 1 !important
            }

            .order-xl-2 {
                order: 2 !important
            }

            .order-xl-3 {
                order: 3 !important
            }

            .order-xl-4 {
                order: 4 !important
            }

            .order-xl-5 {
                order: 5 !important
            }

            .order-xl-last {
                order: 6 !important
            }

            .m-xl-0 {
                margin: 0 !important
            }

            .m-xl-1 {
                margin: .25rem !important
            }

            .m-xl-2 {
                margin: .5rem !important
            }

            .m-xl-3 {
                margin: 1rem !important
            }

            .m-xl-4 {
                margin: 1.5rem !important
            }

            .m-xl-5 {
                margin: 3rem !important
            }

            .m-xl-auto {
                margin: auto !important
            }

            .mx-xl-0 {
                margin-right: 0 !important;
                margin-left: 0 !important
            }

            .mx-xl-1 {
                margin-right: .25rem !important;
                margin-left: .25rem !important
            }

            .mx-xl-2 {
                margin-right: .5rem !important;
                margin-left: .5rem !important
            }

            .mx-xl-3 {
                margin-right: 1rem !important;
                margin-left: 1rem !important
            }

            .mx-xl-4 {
                margin-right: 1.5rem !important;
                margin-left: 1.5rem !important
            }

            .mx-xl-5 {
                margin-right: 3rem !important;
                margin-left: 3rem !important
            }

            .mx-xl-auto {
                margin-right: auto !important;
                margin-left: auto !important
            }

            .my-xl-0 {
                margin-top: 0 !important;
                margin-bottom: 0 !important
            }

            .my-xl-1 {
                margin-top: .25rem !important;
                margin-bottom: .25rem !important
            }

            .my-xl-2 {
                margin-top: .5rem !important;
                margin-bottom: .5rem !important
            }

            .my-xl-3 {
                margin-top: 1rem !important;
                margin-bottom: 1rem !important
            }

            .my-xl-4 {
                margin-top: 1.5rem !important;
                margin-bottom: 1.5rem !important
            }

            .my-xl-5 {
                margin-top: 3rem !important;
                margin-bottom: 3rem !important
            }

            .my-xl-auto {
                margin-top: auto !important;
                margin-bottom: auto !important
            }

            .mt-xl-0 {
                margin-top: 0 !important
            }

            .mt-xl-1 {
                margin-top: .25rem !important
            }

            .mt-xl-2 {
                margin-top: .5rem !important
            }

            .mt-xl-3 {
                margin-top: 1rem !important
            }

            .mt-xl-4 {
                margin-top: 1.5rem !important
            }

            .mt-xl-5 {
                margin-top: 3rem !important
            }

            .mt-xl-auto {
                margin-top: auto !important
            }

            .me-xl-0 {
                margin-right: 0 !important
            }

            .me-xl-1 {
                margin-right: .25rem !important
            }

            .me-xl-2 {
                margin-right: .5rem !important
            }

            .me-xl-3 {
                margin-right: 1rem !important
            }

            .me-xl-4 {
                margin-right: 1.5rem !important
            }

            .me-xl-5 {
                margin-right: 3rem !important
            }

            .me-xl-auto {
                margin-right: auto !important
            }

            .mb-xl-0 {
                margin-bottom: 0 !important
            }

            .mb-xl-1 {
                margin-bottom: .25rem !important
            }

            .mb-xl-2 {
                margin-bottom: .5rem !important
            }

            .mb-xl-3 {
                margin-bottom: 1rem !important
            }

            .mb-xl-4 {
                margin-bottom: 1.5rem !important
            }

            .mb-xl-5 {
                margin-bottom: 3rem !important
            }

            .mb-xl-auto {
                margin-bottom: auto !important
            }

            .ms-xl-0 {
                margin-left: 0 !important
            }

            .ms-xl-1 {
                margin-left: .25rem !important
            }

            .ms-xl-2 {
                margin-left: .5rem !important
            }

            .ms-xl-3 {
                margin-left: 1rem !important
            }

            .ms-xl-4 {
                margin-left: 1.5rem !important
            }

            .ms-xl-5 {
                margin-left: 3rem !important
            }

            .ms-xl-auto {
                margin-left: auto !important
            }

            .p-xl-0 {
                padding: 0 !important
            }

            .p-xl-1 {
                padding: .25rem !important
            }

            .p-xl-2 {
                padding: .5rem !important
            }

            .p-xl-3 {
                padding: 1rem !important
            }

            .p-xl-4 {
                padding: 1.5rem !important
            }

            .p-xl-5 {
                padding: 3rem !important
            }

            .px-xl-0 {
                padding-right: 0 !important;
                padding-left: 0 !important
            }

            .px-xl-1 {
                padding-right: .25rem !important;
                padding-left: .25rem !important
            }

            .px-xl-2 {
                padding-right: .5rem !important;
                padding-left: .5rem !important
            }

            .px-xl-3 {
                padding-right: 1rem !important;
                padding-left: 1rem !important
            }

            .px-xl-4 {
                padding-right: 1.5rem !important;
                padding-left: 1.5rem !important
            }

            .px-xl-5 {
                padding-right: 3rem !important;
                padding-left: 3rem !important
            }

            .py-xl-0 {
                padding-top: 0 !important;
                padding-bottom: 0 !important
            }

            .py-xl-1 {
                padding-top: .25rem !important;
                padding-bottom: .25rem !important
            }

            .py-xl-2 {
                padding-top: .5rem !important;
                padding-bottom: .5rem !important
            }

            .py-xl-3 {
                padding-top: 1rem !important;
                padding-bottom: 1rem !important
            }

            .py-xl-4 {
                padding-top: 1.5rem !important;
                padding-bottom: 1.5rem !important
            }

            .py-xl-5 {
                padding-top: 3rem !important;
                padding-bottom: 3rem !important
            }

            .pt-xl-0 {
                padding-top: 0 !important
            }

            .pt-xl-1 {
                padding-top: .25rem !important
            }

            .pt-xl-2 {
                padding-top: .5rem !important
            }

            .pt-xl-3 {
                padding-top: 1rem !important
            }

            .pt-xl-4 {
                padding-top: 1.5rem !important
            }

            .pt-xl-5 {
                padding-top: 3rem !important
            }

            .pe-xl-0 {
                padding-right: 0 !important
            }

            .pe-xl-1 {
                padding-right: .25rem !important
            }

            .pe-xl-2 {
                padding-right: .5rem !important
            }

            .pe-xl-3 {
                padding-right: 1rem !important
            }

            .pe-xl-4 {
                padding-right: 1.5rem !important
            }

            .pe-xl-5 {
                padding-right: 3rem !important
            }

            .pb-xl-0 {
                padding-bottom: 0 !important
            }

            .pb-xl-1 {
                padding-bottom: .25rem !important
            }

            .pb-xl-2 {
                padding-bottom: .5rem !important
            }

            .pb-xl-3 {
                padding-bottom: 1rem !important
            }

            .pb-xl-4 {
                padding-bottom: 1.5rem !important
            }

            .pb-xl-5 {
                padding-bottom: 3rem !important
            }

            .ps-xl-0 {
                padding-left: 0 !important
            }

            .ps-xl-1 {
                padding-left: .25rem !important
            }

            .ps-xl-2 {
                padding-left: .5rem !important
            }

            .ps-xl-3 {
                padding-left: 1rem !important
            }

            .ps-xl-4 {
                padding-left: 1.5rem !important
            }

            .ps-xl-5 {
                padding-left: 3rem !important
            }

            .gap-xl-0 {
                gap: 0 !important
            }

            .gap-xl-1 {
                gap: .25rem !important
            }

            .gap-xl-2 {
                gap: .5rem !important
            }

            .gap-xl-3 {
                gap: 1rem !important
            }

            .gap-xl-4 {
                gap: 1.5rem !important
            }

            .gap-xl-5 {
                gap: 3rem !important
            }

            .row-gap-xl-0 {
                row-gap: 0 !important
            }

            .row-gap-xl-1 {
                row-gap: .25rem !important
            }

            .row-gap-xl-2 {
                row-gap: .5rem !important
            }

            .row-gap-xl-3 {
                row-gap: 1rem !important
            }

            .row-gap-xl-4 {
                row-gap: 1.5rem !important
            }

            .row-gap-xl-5 {
                row-gap: 3rem !important
            }

            .column-gap-xl-0 {
                -moz-column-gap: 0 !important;
                column-gap: 0 !important
            }

            .column-gap-xl-1 {
                -moz-column-gap: 0.25rem !important;
                column-gap: .25rem !important
            }

            .column-gap-xl-2 {
                -moz-column-gap: 0.5rem !important;
                column-gap: .5rem !important
            }

            .column-gap-xl-3 {
                -moz-column-gap: 1rem !important;
                column-gap: 1rem !important
            }

            .column-gap-xl-4 {
                -moz-column-gap: 1.5rem !important;
                column-gap: 1.5rem !important
            }

            .column-gap-xl-5 {
                -moz-column-gap: 3rem !important;
                column-gap: 3rem !important
            }

            .text-xl-start {
                text-align: left !important
            }

            .text-xl-end {
                text-align: right !important
            }

            .text-xl-center {
                text-align: center !important
            }
        }

        @media (min-width:1400px) {
            .float-xxl-start {
                float: left !important
            }

            .float-xxl-end {
                float: right !important
            }

            .float-xxl-none {
                float: none !important
            }

            .object-fit-xxl-contain {
                -o-object-fit: contain !important;
                object-fit: contain !important
            }

            .object-fit-xxl-cover {
                -o-object-fit: cover !important;
                object-fit: cover !important
            }

            .object-fit-xxl-fill {
                -o-object-fit: fill !important;
                object-fit: fill !important
            }

            .object-fit-xxl-scale {
                -o-object-fit: scale-down !important;
                object-fit: scale-down !important
            }

            .object-fit-xxl-none {
                -o-object-fit: none !important;
                object-fit: none !important
            }

            .d-xxl-inline {
                display: inline !important
            }

            .d-xxl-inline-block {
                display: inline-block !important
            }

            .d-xxl-block {
                display: block !important
            }

            .d-xxl-grid {
                display: grid !important
            }

            .d-xxl-inline-grid {
                display: inline-grid !important
            }

            .d-xxl-table {
                display: table !important
            }

            .d-xxl-table-row {
                display: table-row !important
            }

            .d-xxl-table-cell {
                display: table-cell !important
            }

            .d-xxl-flex {
                display: flex !important
            }

            .d-xxl-inline-flex {
                display: inline-flex !important
            }

            .d-xxl-none {
                display: none !important
            }

            .flex-xxl-fill {
                flex: 1 1 auto !important
            }

            .flex-xxl-row {
                flex-direction: row !important
            }

            .flex-xxl-column {
                flex-direction: column !important
            }

            .flex-xxl-row-reverse {
                flex-direction: row-reverse !important
            }

            .flex-xxl-column-reverse {
                flex-direction: column-reverse !important
            }

            .flex-xxl-grow-0 {
                flex-grow: 0 !important
            }

            .flex-xxl-grow-1 {
                flex-grow: 1 !important
            }

            .flex-xxl-shrink-0 {
                flex-shrink: 0 !important
            }

            .flex-xxl-shrink-1 {
                flex-shrink: 1 !important
            }

            .flex-xxl-wrap {
                flex-wrap: wrap !important
            }

            .flex-xxl-nowrap {
                flex-wrap: nowrap !important
            }

            .flex-xxl-wrap-reverse {
                flex-wrap: wrap-reverse !important
            }

            .justify-content-xxl-start {
                justify-content: flex-start !important
            }

            .justify-content-xxl-end {
                justify-content: flex-end !important
            }

            .justify-content-xxl-center {
                justify-content: center !important
            }

            .justify-content-xxl-between {
                justify-content: space-between !important
            }

            .justify-content-xxl-around {
                justify-content: space-around !important
            }

            .justify-content-xxl-evenly {
                justify-content: space-evenly !important
            }

            .align-items-xxl-start {
                align-items: flex-start !important
            }

            .align-items-xxl-end {
                align-items: flex-end !important
            }

            .align-items-xxl-center {
                align-items: center !important
            }

            .align-items-xxl-baseline {
                align-items: baseline !important
            }

            .align-items-xxl-stretch {
                align-items: stretch !important
            }

            .align-content-xxl-start {
                align-content: flex-start !important
            }

            .align-content-xxl-end {
                align-content: flex-end !important
            }

            .align-content-xxl-center {
                align-content: center !important
            }

            .align-content-xxl-between {
                align-content: space-between !important
            }

            .align-content-xxl-around {
                align-content: space-around !important
            }

            .align-content-xxl-stretch {
                align-content: stretch !important
            }

            .align-self-xxl-auto {
                align-self: auto !important
            }

            .align-self-xxl-start {
                align-self: flex-start !important
            }

            .align-self-xxl-end {
                align-self: flex-end !important
            }

            .align-self-xxl-center {
                align-self: center !important
            }

            .align-self-xxl-baseline {
                align-self: baseline !important
            }

            .align-self-xxl-stretch {
                align-self: stretch !important
            }

            .order-xxl-first {
                order: -1 !important
            }

            .order-xxl-0 {
                order: 0 !important
            }

            .order-xxl-1 {
                order: 1 !important
            }

            .order-xxl-2 {
                order: 2 !important
            }

            .order-xxl-3 {
                order: 3 !important
            }

            .order-xxl-4 {
                order: 4 !important
            }

            .order-xxl-5 {
                order: 5 !important
            }

            .order-xxl-last {
                order: 6 !important
            }

            .m-xxl-0 {
                margin: 0 !important
            }

            .m-xxl-1 {
                margin: .25rem !important
            }

            .m-xxl-2 {
                margin: .5rem !important
            }

            .m-xxl-3 {
                margin: 1rem !important
            }

            .m-xxl-4 {
                margin: 1.5rem !important
            }

            .m-xxl-5 {
                margin: 3rem !important
            }

            .m-xxl-auto {
                margin: auto !important
            }

            .mx-xxl-0 {
                margin-right: 0 !important;
                margin-left: 0 !important
            }

            .mx-xxl-1 {
                margin-right: .25rem !important;
                margin-left: .25rem !important
            }

            .mx-xxl-2 {
                margin-right: .5rem !important;
                margin-left: .5rem !important
            }

            .mx-xxl-3 {
                margin-right: 1rem !important;
                margin-left: 1rem !important
            }

            .mx-xxl-4 {
                margin-right: 1.5rem !important;
                margin-left: 1.5rem !important
            }

            .mx-xxl-5 {
                margin-right: 3rem !important;
                margin-left: 3rem !important
            }

            .mx-xxl-auto {
                margin-right: auto !important;
                margin-left: auto !important
            }

            .my-xxl-0 {
                margin-top: 0 !important;
                margin-bottom: 0 !important
            }

            .my-xxl-1 {
                margin-top: .25rem !important;
                margin-bottom: .25rem !important
            }

            .my-xxl-2 {
                margin-top: .5rem !important;
                margin-bottom: .5rem !important
            }

            .my-xxl-3 {
                margin-top: 1rem !important;
                margin-bottom: 1rem !important
            }

            .my-xxl-4 {
                margin-top: 1.5rem !important;
                margin-bottom: 1.5rem !important
            }

            .my-xxl-5 {
                margin-top: 3rem !important;
                margin-bottom: 3rem !important
            }

            .my-xxl-auto {
                margin-top: auto !important;
                margin-bottom: auto !important
            }

            .mt-xxl-0 {
                margin-top: 0 !important
            }

            .mt-xxl-1 {
                margin-top: .25rem !important
            }

            .mt-xxl-2 {
                margin-top: .5rem !important
            }

            .mt-xxl-3 {
                margin-top: 1rem !important
            }

            .mt-xxl-4 {
                margin-top: 1.5rem !important
            }

            .mt-xxl-5 {
                margin-top: 3rem !important
            }

            .mt-xxl-auto {
                margin-top: auto !important
            }

            .me-xxl-0 {
                margin-right: 0 !important
            }

            .me-xxl-1 {
                margin-right: .25rem !important
            }

            .me-xxl-2 {
                margin-right: .5rem !important
            }

            .me-xxl-3 {
                margin-right: 1rem !important
            }

            .me-xxl-4 {
                margin-right: 1.5rem !important
            }

            .me-xxl-5 {
                margin-right: 3rem !important
            }

            .me-xxl-auto {
                margin-right: auto !important
            }

            .mb-xxl-0 {
                margin-bottom: 0 !important
            }

            .mb-xxl-1 {
                margin-bottom: .25rem !important
            }

            .mb-xxl-2 {
                margin-bottom: .5rem !important
            }

            .mb-xxl-3 {
                margin-bottom: 1rem !important
            }

            .mb-xxl-4 {
                margin-bottom: 1.5rem !important
            }

            .mb-xxl-5 {
                margin-bottom: 3rem !important
            }

            .mb-xxl-auto {
                margin-bottom: auto !important
            }

            .ms-xxl-0 {
                margin-left: 0 !important
            }

            .ms-xxl-1 {
                margin-left: .25rem !important
            }

            .ms-xxl-2 {
                margin-left: .5rem !important
            }

            .ms-xxl-3 {
                margin-left: 1rem !important
            }

            .ms-xxl-4 {
                margin-left: 1.5rem !important
            }

            .ms-xxl-5 {
                margin-left: 3rem !important
            }

            .ms-xxl-auto {
                margin-left: auto !important
            }

            .p-xxl-0 {
                padding: 0 !important
            }

            .p-xxl-1 {
                padding: .25rem !important
            }

            .p-xxl-2 {
                padding: .5rem !important
            }

            .p-xxl-3 {
                padding: 1rem !important
            }

            .p-xxl-4 {
                padding: 1.5rem !important
            }

            .p-xxl-5 {
                padding: 3rem !important
            }

            .px-xxl-0 {
                padding-right: 0 !important;
                padding-left: 0 !important
            }

            .px-xxl-1 {
                padding-right: .25rem !important;
                padding-left: .25rem !important
            }

            .px-xxl-2 {
                padding-right: .5rem !important;
                padding-left: .5rem !important
            }

            .px-xxl-3 {
                padding-right: 1rem !important;
                padding-left: 1rem !important
            }

            .px-xxl-4 {
                padding-right: 1.5rem !important;
                padding-left: 1.5rem !important
            }

            .px-xxl-5 {
                padding-right: 3rem !important;
                padding-left: 3rem !important
            }

            .py-xxl-0 {
                padding-top: 0 !important;
                padding-bottom: 0 !important
            }

            .py-xxl-1 {
                padding-top: .25rem !important;
                padding-bottom: .25rem !important
            }

            .py-xxl-2 {
                padding-top: .5rem !important;
                padding-bottom: .5rem !important
            }

            .py-xxl-3 {
                padding-top: 1rem !important;
                padding-bottom: 1rem !important
            }

            .py-xxl-4 {
                padding-top: 1.5rem !important;
                padding-bottom: 1.5rem !important
            }

            .py-xxl-5 {
                padding-top: 3rem !important;
                padding-bottom: 3rem !important
            }

            .pt-xxl-0 {
                padding-top: 0 !important
            }

            .pt-xxl-1 {
                padding-top: .25rem !important
            }

            .pt-xxl-2 {
                padding-top: .5rem !important
            }

            .pt-xxl-3 {
                padding-top: 1rem !important
            }

            .pt-xxl-4 {
                padding-top: 1.5rem !important
            }

            .pt-xxl-5 {
                padding-top: 3rem !important
            }

            .pe-xxl-0 {
                padding-right: 0 !important
            }

            .pe-xxl-1 {
                padding-right: .25rem !important
            }

            .pe-xxl-2 {
                padding-right: .5rem !important
            }

            .pe-xxl-3 {
                padding-right: 1rem !important
            }

            .pe-xxl-4 {
                padding-right: 1.5rem !important
            }

            .pe-xxl-5 {
                padding-right: 3rem !important
            }

            .pb-xxl-0 {
                padding-bottom: 0 !important
            }

            .pb-xxl-1 {
                padding-bottom: .25rem !important
            }

            .pb-xxl-2 {
                padding-bottom: .5rem !important
            }

            .pb-xxl-3 {
                padding-bottom: 1rem !important
            }

            .pb-xxl-4 {
                padding-bottom: 1.5rem !important
            }

            .pb-xxl-5 {
                padding-bottom: 3rem !important
            }

            .ps-xxl-0 {
                padding-left: 0 !important
            }

            .ps-xxl-1 {
                padding-left: .25rem !important
            }

            .ps-xxl-2 {
                padding-left: .5rem !important
            }

            .ps-xxl-3 {
                padding-left: 1rem !important
            }

            .ps-xxl-4 {
                padding-left: 1.5rem !important
            }

            .ps-xxl-5 {
                padding-left: 3rem !important
            }

            .gap-xxl-0 {
                gap: 0 !important
            }

            .gap-xxl-1 {
                gap: .25rem !important
            }

            .gap-xxl-2 {
                gap: .5rem !important
            }

            .gap-xxl-3 {
                gap: 1rem !important
            }

            .gap-xxl-4 {
                gap: 1.5rem !important
            }

            .gap-xxl-5 {
                gap: 3rem !important
            }

            .row-gap-xxl-0 {
                row-gap: 0 !important
            }

            .row-gap-xxl-1 {
                row-gap: .25rem !important
            }

            .row-gap-xxl-2 {
                row-gap: .5rem !important
            }

            .row-gap-xxl-3 {
                row-gap: 1rem !important
            }

            .row-gap-xxl-4 {
                row-gap: 1.5rem !important
            }

            .row-gap-xxl-5 {
                row-gap: 3rem !important
            }

            .column-gap-xxl-0 {
                -moz-column-gap: 0 !important;
                column-gap: 0 !important
            }

            .column-gap-xxl-1 {
                -moz-column-gap: 0.25rem !important;
                column-gap: .25rem !important
            }

            .column-gap-xxl-2 {
                -moz-column-gap: 0.5rem !important;
                column-gap: .5rem !important
            }

            .column-gap-xxl-3 {
                -moz-column-gap: 1rem !important;
                column-gap: 1rem !important
            }

            .column-gap-xxl-4 {
                -moz-column-gap: 1.5rem !important;
                column-gap: 1.5rem !important
            }

            .column-gap-xxl-5 {
                -moz-column-gap: 3rem !important;
                column-gap: 3rem !important
            }

            .text-xxl-start {
                text-align: left !important
            }

            .text-xxl-end {
                text-align: right !important
            }

            .text-xxl-center {
                text-align: center !important
            }
        }

        @media (min-width:1200px) {
            .fs-1 {
                font-size: 2.5rem !important
            }

            .fs-2 {
                font-size: 2rem !important
            }

            .fs-3 {
                font-size: 1.75rem !important
            }

            .fs-4 {
                font-size: 1.5rem !important
            }
        }

        @media print {
            .d-print-inline {
                display: inline !important
            }

            .d-print-inline-block {
                display: inline-block !important
            }

            .d-print-block {
                display: block !important
            }

            .d-print-grid {
                display: grid !important
            }

            .d-print-inline-grid {
                display: inline-grid !important
            }

            .d-print-table {
                display: table !important
            }

            .d-print-table-row {
                display: table-row !important
            }

            .d-print-table-cell {
                display: table-cell !important
            }

            .d-print-flex {
                display: flex !important
            }

            .d-print-inline-flex {
                display: inline-flex !important
            }

            .d-print-none {
                display: none !important
            }
        }

        /*# sourceMappingURL=bootstrap.min.css.map */
        .bd-placeholder-img {
            font-size: 1.125rem;
            text-anchor: middle;
            -webkit-user-select: none;
            -moz-user-select: none;
            user-select: none;
        }

        @media (min-width: 768px) {
            .bd-placeholder-img-lg {
                font-size: 3.5rem;
            }
        }

        .b-example-divider {
            width: 100%;
            height: 3rem;
            background-color: rgba(0, 0, 0, .1);
            border: solid rgba(0, 0, 0, .15);
            border-width: 1px 0;
            box-shadow: inset 0 .5em 1.5em rgba(14, 204, 204, 0.1), inset 0 .125em .5em rgba(0, 0, 0, .15);
        }

        .b-example-vr {
            flex-shrink: 0;
            width: 1.5rem;
            height: 100vh;
        }

        .bi {
            vertical-align: -.125em;
            fill: currentColor;
        }

        .nav-scroller {
            position: relative;
            z-index: 2;
            height: 2.75rem;
            overflow-y: hidden;
        }

        .nav-scroller .nav {
            display: flex;
            flex-wrap: nowrap;
            padding-bottom: 1rem;
            margin-top: -1px;
            overflow-x: auto;
            text-align: center;
            white-space: nowrap;
            -webkit-overflow-scrolling: touch;
        }

        .btn-bd-primary {
            --bd-violet-bg: #712cf9;
            --bd-violet-rgb: 112.520718, 44.062154, 249.437846;

            --bs-btn-font-weight: 600;
            --bs-btn-color: var(--bs-white);
            --bs-btn-bg: var(--bd-violet-bg);
            --bs-btn-border-color: var(--bd-violet-bg);
            --bs-btn-hover-color: var(--bs-white);
            --bs-btn-hover-bg: #6528e0;
            --bs-btn-hover-border-color: #6528e0;
            --bs-btn-focus-shadow-rgb: var(--bd-violet-rgb);
            --bs-btn-active-color: var(--bs-btn-hover-color);
            --bs-btn-active-bg: #5a23c8;
            --bs-btn-active-border-color: #5a23c8;
        }

        .bd-mode-toggle {
            z-index: 1500;
        }

        body {
            scroll-behavior: smooth;
        }

        /*!
 * Bootstrap Docs (https://getbootstrap.com/)
 * Copyright 2011-2023 The Bootstrap Authors
 * Licensed under the Creative Commons Attribution 3.0 Unported License.
 * For details, see https://creativecommons.org/licenses/by/3.0/.
 */
        :root {
            --bs-breakpoint-xs: 0;
            --bs-breakpoint-sm: 576px;
            --bs-breakpoint-md: 768px;
            --bs-breakpoint-lg: 992px;
            --bs-breakpoint-xl: 1200px;
            --bs-breakpoint-xxl: 1400px
        }

        .grid {
            display: grid;
            grid-template-rows: repeat(var(--bs-rows, 1), 1fr);
            grid-template-columns: repeat(var(--bs-columns, 12), 1fr);
            gap: var(--bs-gap, 1.5rem)
        }

        .grid .g-col-1 {
            grid-column: auto/span 1
        }

        .grid .g-col-2 {
            grid-column: auto/span 2
        }

        .grid .g-col-3 {
            grid-column: auto/span 3
        }

        .grid .g-col-4 {
            grid-column: auto/span 4
        }

        .grid .g-col-5 {
            grid-column: auto/span 5
        }

        .grid .g-col-6 {
            grid-column: auto/span 6
        }

        .grid .g-col-7 {
            grid-column: auto/span 7
        }

        .grid .g-col-8 {
            grid-column: auto/span 8
        }

        .grid .g-col-9 {
            grid-column: auto/span 9
        }

        .grid .g-col-10 {
            grid-column: auto/span 10
        }

        .grid .g-col-11 {
            grid-column: auto/span 11
        }

        .grid .g-col-12 {
            grid-column: auto/span 12
        }

        .grid .g-start-1 {
            grid-column-start: 1
        }

        .grid .g-start-2 {
            grid-column-start: 2
        }

        .grid .g-start-3 {
            grid-column-start: 3
        }

        .grid .g-start-4 {
            grid-column-start: 4
        }

        .grid .g-start-5 {
            grid-column-start: 5
        }

        .grid .g-start-6 {
            grid-column-start: 6
        }

        .grid .g-start-7 {
            grid-column-start: 7
        }

        .grid .g-start-8 {
            grid-column-start: 8
        }

        .grid .g-start-9 {
            grid-column-start: 9
        }

        .grid .g-start-10 {
            grid-column-start: 10
        }

        .grid .g-start-11 {
            grid-column-start: 11
        }

        @media (min-width: 576px) {
            .grid .g-col-sm-1 {
                grid-column: auto/span 1
            }

            .grid .g-col-sm-2 {
                grid-column: auto/span 2
            }

            .grid .g-col-sm-3 {
                grid-column: auto/span 3
            }

            .grid .g-col-sm-4 {
                grid-column: auto/span 4
            }

            .grid .g-col-sm-5 {
                grid-column: auto/span 5
            }

            .grid .g-col-sm-6 {
                grid-column: auto/span 6
            }

            .grid .g-col-sm-7 {
                grid-column: auto/span 7
            }

            .grid .g-col-sm-8 {
                grid-column: auto/span 8
            }

            .grid .g-col-sm-9 {
                grid-column: auto/span 9
            }

            .grid .g-col-sm-10 {
                grid-column: auto/span 10
            }

            .grid .g-col-sm-11 {
                grid-column: auto/span 11
            }

            .grid .g-col-sm-12 {
                grid-column: auto/span 12
            }

            .grid .g-start-sm-1 {
                grid-column-start: 1
            }

            .grid .g-start-sm-2 {
                grid-column-start: 2
            }

            .grid .g-start-sm-3 {
                grid-column-start: 3
            }

            .grid .g-start-sm-4 {
                grid-column-start: 4
            }

            .grid .g-start-sm-5 {
                grid-column-start: 5
            }

            .grid .g-start-sm-6 {
                grid-column-start: 6
            }

            .grid .g-start-sm-7 {
                grid-column-start: 7
            }

            .grid .g-start-sm-8 {
                grid-column-start: 8
            }

            .grid .g-start-sm-9 {
                grid-column-start: 9
            }

            .grid .g-start-sm-10 {
                grid-column-start: 10
            }

            .grid .g-start-sm-11 {
                grid-column-start: 11
            }
        }

        @media (min-width: 768px) {
            .grid .g-col-md-1 {
                grid-column: auto/span 1
            }

            .grid .g-col-md-2 {
                grid-column: auto/span 2
            }

            .grid .g-col-md-3 {
                grid-column: auto/span 3
            }

            .grid .g-col-md-4 {
                grid-column: auto/span 4
            }

            .grid .g-col-md-5 {
                grid-column: auto/span 5
            }

            .grid .g-col-md-6 {
                grid-column: auto/span 6
            }

            .grid .g-col-md-7 {
                grid-column: auto/span 7
            }

            .grid .g-col-md-8 {
                grid-column: auto/span 8
            }

            .grid .g-col-md-9 {
                grid-column: auto/span 9
            }

            .grid .g-col-md-10 {
                grid-column: auto/span 10
            }

            .grid .g-col-md-11 {
                grid-column: auto/span 11
            }

            .grid .g-col-md-12 {
                grid-column: auto/span 12
            }

            .grid .g-start-md-1 {
                grid-column-start: 1
            }

            .grid .g-start-md-2 {
                grid-column-start: 2
            }

            .grid .g-start-md-3 {
                grid-column-start: 3
            }

            .grid .g-start-md-4 {
                grid-column-start: 4
            }

            .grid .g-start-md-5 {
                grid-column-start: 5
            }

            .grid .g-start-md-6 {
                grid-column-start: 6
            }

            .grid .g-start-md-7 {
                grid-column-start: 7
            }

            .grid .g-start-md-8 {
                grid-column-start: 8
            }

            .grid .g-start-md-9 {
                grid-column-start: 9
            }

            .grid .g-start-md-10 {
                grid-column-start: 10
            }

            .grid .g-start-md-11 {
                grid-column-start: 11
            }
        }

        @media (min-width: 992px) {
            .grid .g-col-lg-1 {
                grid-column: auto/span 1
            }

            .grid .g-col-lg-2 {
                grid-column: auto/span 2
            }

            .grid .g-col-lg-3 {
                grid-column: auto/span 3
            }

            .grid .g-col-lg-4 {
                grid-column: auto/span 4
            }

            .grid .g-col-lg-5 {
                grid-column: auto/span 5
            }

            .grid .g-col-lg-6 {
                grid-column: auto/span 6
            }

            .grid .g-col-lg-7 {
                grid-column: auto/span 7
            }

            .grid .g-col-lg-8 {
                grid-column: auto/span 8
            }

            .grid .g-col-lg-9 {
                grid-column: auto/span 9
            }

            .grid .g-col-lg-10 {
                grid-column: auto/span 10
            }

            .grid .g-col-lg-11 {
                grid-column: auto/span 11
            }

            .grid .g-col-lg-12 {
                grid-column: auto/span 12
            }

            .grid .g-start-lg-1 {
                grid-column-start: 1
            }

            .grid .g-start-lg-2 {
                grid-column-start: 2
            }

            .grid .g-start-lg-3 {
                grid-column-start: 3
            }

            .grid .g-start-lg-4 {
                grid-column-start: 4
            }

            .grid .g-start-lg-5 {
                grid-column-start: 5
            }

            .grid .g-start-lg-6 {
                grid-column-start: 6
            }

            .grid .g-start-lg-7 {
                grid-column-start: 7
            }

            .grid .g-start-lg-8 {
                grid-column-start: 8
            }

            .grid .g-start-lg-9 {
                grid-column-start: 9
            }

            .grid .g-start-lg-10 {
                grid-column-start: 10
            }

            .grid .g-start-lg-11 {
                grid-column-start: 11
            }
        }

        @media (min-width: 1200px) {
            .grid .g-col-xl-1 {
                grid-column: auto/span 1
            }

            .grid .g-col-xl-2 {
                grid-column: auto/span 2
            }

            .grid .g-col-xl-3 {
                grid-column: auto/span 3
            }

            .grid .g-col-xl-4 {
                grid-column: auto/span 4
            }

            .grid .g-col-xl-5 {
                grid-column: auto/span 5
            }

            .grid .g-col-xl-6 {
                grid-column: auto/span 6
            }

            .grid .g-col-xl-7 {
                grid-column: auto/span 7
            }

            .grid .g-col-xl-8 {
                grid-column: auto/span 8
            }

            .grid .g-col-xl-9 {
                grid-column: auto/span 9
            }

            .grid .g-col-xl-10 {
                grid-column: auto/span 10
            }

            .grid .g-col-xl-11 {
                grid-column: auto/span 11
            }

            .grid .g-col-xl-12 {
                grid-column: auto/span 12
            }

            .grid .g-start-xl-1 {
                grid-column-start: 1
            }

            .grid .g-start-xl-2 {
                grid-column-start: 2
            }

            .grid .g-start-xl-3 {
                grid-column-start: 3
            }

            .grid .g-start-xl-4 {
                grid-column-start: 4
            }

            .grid .g-start-xl-5 {
                grid-column-start: 5
            }

            .grid .g-start-xl-6 {
                grid-column-start: 6
            }

            .grid .g-start-xl-7 {
                grid-column-start: 7
            }

            .grid .g-start-xl-8 {
                grid-column-start: 8
            }

            .grid .g-start-xl-9 {
                grid-column-start: 9
            }

            .grid .g-start-xl-10 {
                grid-column-start: 10
            }

            .grid .g-start-xl-11 {
                grid-column-start: 11
            }
        }

        @media (min-width: 1400px) {
            .grid .g-col-xxl-1 {
                grid-column: auto/span 1
            }

            .grid .g-col-xxl-2 {
                grid-column: auto/span 2
            }

            .grid .g-col-xxl-3 {
                grid-column: auto/span 3
            }

            .grid .g-col-xxl-4 {
                grid-column: auto/span 4
            }

            .grid .g-col-xxl-5 {
                grid-column: auto/span 5
            }

            .grid .g-col-xxl-6 {
                grid-column: auto/span 6
            }

            .grid .g-col-xxl-7 {
                grid-column: auto/span 7
            }

            .grid .g-col-xxl-8 {
                grid-column: auto/span 8
            }

            .grid .g-col-xxl-9 {
                grid-column: auto/span 9
            }

            .grid .g-col-xxl-10 {
                grid-column: auto/span 10
            }

            .grid .g-col-xxl-11 {
                grid-column: auto/span 11
            }

            .grid .g-col-xxl-12 {
                grid-column: auto/span 12
            }

            .grid .g-start-xxl-1 {
                grid-column-start: 1
            }

            .grid .g-start-xxl-2 {
                grid-column-start: 2
            }

            .grid .g-start-xxl-3 {
                grid-column-start: 3
            }

            .grid .g-start-xxl-4 {
                grid-column-start: 4
            }

            .grid .g-start-xxl-5 {
                grid-column-start: 5
            }

            .grid .g-start-xxl-6 {
                grid-column-start: 6
            }

            .grid .g-start-xxl-7 {
                grid-column-start: 7
            }

            .grid .g-start-xxl-8 {
                grid-column-start: 8
            }

            .grid .g-start-xxl-9 {
                grid-column-start: 9
            }

            .grid .g-start-xxl-10 {
                grid-column-start: 10
            }

            .grid .g-start-xxl-11 {
                grid-column-start: 11
            }
        }

        :root,
        [data-bs-theme="light"] {
            --bd-purple: #4c0bce;
            --bd-violet: #712cf9;
            --bd-accent: #ffe484;
            --bd-violet-rgb: 112.520718, 44.062154, 249.437846;
            --bd-accent-rgb: 255, 228, 132;
            --bd-pink-rgb: 214, 51, 132;
            --bd-teal-rgb: 32, 201, 151;
            --bd-violet-bg: var(--bd-violet);
            --bd-toc-color: var(--bd-violet);
            --bd-sidebar-link-bg: rgba(var(--bd-violet-rgb), .1);
            --bd-callout-link: 10, 88, 202;
            --bd-callout-code-color: #ab296a;
            --bd-pre-bg: var(--bs-tertiary-bg)
        }

        [data-bs-theme="dark"] {
            --bd-violet: #9461fb;
            --bd-violet-bg: #712cf9;
            --bd-toc-color: var(--bs-emphasis-color);
            --bd-sidebar-link-bg: rgba(84, 33, 187, .5);
            --bd-callout-link: 110, 168, 254;
            --bd-callout-code-color: #e685b5;
            --bd-pre-bg: #1b1f22
        }

        .bd-navbar {
            padding: .75rem 0;
            background-color: transparent;
            box-shadow: 0 0.5rem 1rem rgba(0, 0, 0, 0.15), inset 0 -1px 0 rgba(255, 255, 255, 0.15)
        }

        .bd-navbar::after {
            position: absolute;
            inset: 0;
            z-index: -1;
            display: block;
            content: "";
            background-color: #0351a0;
        }

        @media (max-width: 991.98px) {
            .bd-navbar .bd-navbar-toggle {
                width: 4.25rem
            }
        }

        .bd-navbar .navbar-toggler {
            padding: 0;
            margin-right: -.5rem;
            border: 0
        }

        .bd-navbar .navbar-toggler:first-child {
            margin-left: -.5rem
        }

        .bd-navbar .navbar-toggler .bi {
            width: 1.5rem;
            height: 1.5rem
        }

        .bd-navbar .navbar-toggler:focus {
            box-shadow: none
        }

        .bd-navbar .navbar-brand {
            color: #fff;
            transition: transform 0.2s ease-in-out
        }

        @media (prefers-reduced-motion: reduce) {
            .bd-navbar .navbar-brand {
                transition: none
            }
        }

        .bd-navbar .navbar-brand:hover {
            transform: rotate(-5deg) scale(1.1)
        }

        .bd-navbar .navbar-toggler,
        .bd-navbar .nav-link {
            padding-right: .25rem;
            padding-left: .25rem;
            color: rgba(255, 255, 255, 0.85)
        }

        .bd-navbar .navbar-toggler:hover,
        .bd-navbar .navbar-toggler:focus,
        .bd-navbar .nav-link:hover,
        .bd-navbar .nav-link:focus {
            color: #fff
        }

        .bd-navbar .navbar-toggler.active,
        .bd-navbar .nav-link.active {
            font-weight: 600;
            color: #fff
        }

        .bd-navbar .navbar-nav-svg {
            display: inline-block;
            vertical-align: -.125rem
        }

        .bd-navbar .offcanvas-lg {
            background-color: var(--bd-violet-bg);
            border-left: 0
        }

        @media (max-width: 991.98px) {
            .bd-navbar .offcanvas-lg {
                box-shadow: 0 1rem 3rem rgba(0, 0, 0, 0.175)
            }
        }

        .bd-navbar .dropdown-toggle:focus:not(:focus-visible) {
            outline: 0
        }

        .bd-navbar .dropdown-menu {
            --bs-dropdown-min-width: 12rem;
            --bs-dropdown-padding-x: .25rem;
            --bs-dropdown-padding-y: .25rem;
            --bs-dropdown-link-hover-bg: rgba(var(--bd-violet-rgb), .1);
            --bs-dropdown-link-active-bg: rgba(var(--bd-violet-rgb), 1);
            --bs-dropdown-font-size: .875rem;
            font-size: .875rem;
            border-radius: .5rem;
            box-shadow: 0 0.5rem 1rem rgba(0, 0, 0, 0.15)
        }

        .bd-navbar .dropdown-menu li+li {
            margin-top: .125rem
        }

        .bd-navbar .dropdown-menu .dropdown-item {
            border-radius: .25rem
        }

        .bd-navbar .dropdown-menu .dropdown-item:active .bi {
            color: inherit !important
        }

        .bd-navbar .dropdown-menu .active {
            font-weight: 600
        }

        .bd-navbar .dropdown-menu .active .bi {
            display: block !important
        }

        .bd-navbar .dropdown-menu-end {
            --bs-dropdown-min-width: 8rem
        }

        [data-bs-theme="dark"] .bd-navbar {
            box-shadow: 0 0.5rem 1rem rgba(0, 0, 0, 0.15), inset 0 -1px 0 rgba(255, 255, 255, 0.15)
        }

        :root {
            --docsearch-primary-color: var(--bd-violet);
            --docsearch-logo-color: var(--bd-violet)
        }

        [data-bs-theme="dark"] {
            --docsearch-text-color: #f5f6f7;
            --docsearch-container-background: rgba(9, 10, 17, .8);
            --docsearch-modal-background: #15172a;
            --docsearch-modal-shadow: inset 1px 1px 0 0 #2c2e40, 0 3px 8px 0 #000309;
            --docsearch-searchbox-background: #090a11;
            --docsearch-searchbox-focus-background: #000;
            --docsearch-hit-color: #bec3c9;
            --docsearch-hit-shadow: none;
            --docsearch-hit-background: #090a11;
            --docsearch-key-gradient: linear-gradient(-26.5deg, #565872, #31355b);
            --docsearch-key-shadow: inset 0 -2px 0 0 #282d55, inset 0 0 1px 1px #51577d, 0 2px 2px 0 rgba(3, 4, 9, .3);
            --docsearch-footer-background: #1e2136;
            --docsearch-footer-shadow: inset 0 1px 0 0 rgba(73, 76, 106, .5), 0 -4px 8px 0 rgba(0, 0, 0, .2);
            --docsearch-muted-color: #7f8497
        }

        .bd-search {
            position: relative
        }

        @media (min-width: 992px) {
            .bd-search {
                position: absolute;
                top: .875rem;
                left: 50%;
                width: 200px;
                margin-left: -100px
            }
        }

        @media (min-width: 1200px) {
            .bd-search {
                width: 280px;
                margin-left: -140px
            }
        }

        .DocSearch-Container {
            --docsearch-muted-color: var(--bs-secondary-color);
            --docsearch-hit-shadow: none;
            z-index: 2000;
            cursor: auto
        }

        @media (min-width: 992px) {
            .DocSearch-Container {
                padding-top: 4rem
            }
        }

        .DocSearch-Button {
            --docsearch-searchbox-background: rgba(0, 0, 0, 0.1);
            --docsearch-searchbox-color: #fff;
            --docsearch-searchbox-focus-background: rgba(0, 0, 0, 0.25);
            --docsearch-searchbox-shadow: 0 0 0 0.25rem rgba(255, 228, 132, 0.4);
            --docsearch-text-color: #fff;
            --docsearch-muted-color: rgba(255, 255, 255, 0.65);
            width: 100%;
            height: 38px;
            margin: 0;
            border: 1px solid rgba(255, 255, 255, 0.4);
            border-radius: .375rem
        }

        .DocSearch-Button .DocSearch-Search-Icon {
            opacity: .65
        }

        .DocSearch-Button:active,
        .DocSearch-Button:focus,
        .DocSearch-Button:hover {
            border-color: #ffe484
        }

        .DocSearch-Button:active .DocSearch-Search-Icon,
        .DocSearch-Button:focus .DocSearch-Search-Icon,
        .DocSearch-Button:hover .DocSearch-Search-Icon {
            opacity: 1
        }

        @media (max-width: 991.98px) {

            .DocSearch-Button,
            .DocSearch-Button:hover,
            .DocSearch-Button:focus {
                background: transparent;
                border: 0;
                box-shadow: none
            }

            .DocSearch-Button:focus {
                box-shadow: var(--docsearch-searchbox-shadow)
            }
        }

        @media (max-width: 991.98px) {

            .DocSearch-Button-Keys,
            .DocSearch-Button-Placeholder {
                display: none
            }
        }

        .DocSearch-Button-Keys {
            min-width: 0;
            padding: .125rem .25rem;
            background: rgba(0, 0, 0, 0.25);
            border-radius: .25rem
        }

        .DocSearch-Button-Key {
            top: 0;
            width: auto;
            height: 1.25rem;
            padding-right: .125rem;
            padding-left: .125rem;
            margin-right: 0;
            font-size: .875rem;
            background: none;
            box-shadow: none
        }

        .DocSearch-Commands-Key {
            padding-left: 1px;
            font-size: .875rem;
            background-color: rgba(0, 0, 0, 0.1);
            background-image: none;
            box-shadow: none
        }

        .DocSearch-Form {
            border-radius: var(--bs-border-radius)
        }

        .DocSearch-Hits mark {
            padding: 0
        }

        .DocSearch-Hit {
            padding-bottom: 0;
            border-radius: 0
        }

        .DocSearch-Hit a {
            border-radius: 0;
            border: solid var(--bs-border-color);
            border-width: 0 1px 1px
        }

        .DocSearch-Hit:first-child a {
            border-top-left-radius: var(--bs-border-radius);
            border-top-right-radius: var(--bs-border-radius);
            border-top-width: 1px
        }

        .DocSearch-Hit:last-child a {
            border-bottom-right-radius: var(--bs-border-radius);
            border-bottom-left-radius: var(--bs-border-radius)
        }

        .DocSearch-Hit-icon {
            display: flex;
            align-items: center
        }

        .DocSearch-Logo svg .cls-1,
        .DocSearch-Logo svg .cls-2 {
            fill: var(--docsearch-logo-color)
        }

        .bd-masthead {
            --bd-pink-rgb: 214, 51, 132;
            padding: 3rem 0;
            background-image: linear-gradient(180deg, rgba(var(--bs-body-bg-rgb), 0.01), rgba(var(--bs-body-bg-rgb), 1) 85%), radial-gradient(ellipse at top left, rgba(var(--bs-primary-rgb), 0.5), transparent 50%), radial-gradient(ellipse at top right, rgba(var(--bd-accent-rgb), 0.5), transparent 50%), radial-gradient(ellipse at center right, rgba(var(--bd-violet-rgb), 0.5), transparent 50%), radial-gradient(ellipse at center left, rgba(var(--bd-pink-rgb), 0.5), transparent 50%)
        }

        .bd-masthead h1 {
            --bs-heading-color: var(--bs-emphasis-color);
            font-size: calc(1.525rem + 3.3vw)
        }

        @media (min-width: 1200px) {
            .bd-masthead h1 {
                font-size: 4rem
            }
        }

        .bd-masthead .lead {
            font-size: 1rem;
            font-weight: 400;
            color: var(--bs-secondary-color)
        }

        .bd-masthead .bd-code-snippet {
            margin: 0;
            border-color: var(--bs-border-color-translucent);
            border-width: 1px;
            border-radius: .5rem
        }

        .bd-masthead .highlight {
            width: 100%;
            padding: .5rem 1rem;
            overflow: hidden;
            text-overflow: ellipsis;
            white-space: nowrap;
            background-color: rgba(var(--bs-body-color-rgb), 0.075);
            border-radius: calc(.5rem - 1px)
        }

        @media (min-width: 992px) {
            .bd-masthead .highlight {
                padding-right: 4rem
            }
        }

        .bd-masthead .highlight pre {
            padding: 0;
            margin: .625rem 0;
            overflow: hidden
        }

        .bd-masthead .btn-clipboard {
            position: absolute;
            top: -.625rem;
            right: 0;
            background-color: transparent
        }

        .bd-masthead #carbonads {
            margin-inline: auto
        }

        @media (min-width: 768px) {
            .bd-masthead .lead {
                font-size: calc(1.275rem + .3vw)
            }
        }

        @media (min-width: 768px) and (min-width: 1200px) {
            .bd-masthead .lead {
                font-size: 1.5rem
            }
        }

        .masthead-followup h2,
        .masthead-followup h3,
        .masthead-followup h4 {
            --bs-heading-color: var(--bs-emphasis-color)
        }

        .masthead-followup .lead {
            font-size: 1rem
        }

        @media (min-width: 768px) {
            .masthead-followup .lead {
                font-size: 1.25rem
            }
        }

        .masthead-followup-icon {
            padding: 1rem;
            color: rgba(var(--bg-rgb), 1);
            background-color: rgba(var(--bg-rgb), 0.1);
            background-blend-mode: multiple;
            border-radius: 1rem;
            mix-blend-mode: darken
        }

        .masthead-followup-icon svg {
            filter: drop-shadow(0 1px 1px var(--bs-body-bg))
        }

        .masthead-notice {
            background-color: var(--bd-accent);
            box-shadow: inset 0 -1px 1px rgba(var(--bs-body-color-rgb), 0.15), 0 0.25rem 1.5rem rgba(var(--bs-body-bg-rgb), 0.75)
        }

        .animate-img>img {
            transition: transform 0.2s ease-in-out
        }

        @media (prefers-reduced-motion: reduce) {
            .animate-img>img {
                transition: none
            }
        }

        .animate-img:hover>img {
            transform: scale(1.1)
        }

        [data-bs-theme="dark"] .masthead-followup-icon {
            mix-blend-mode: lighten
        }

        #carbonads {
            position: static;
            display: block;
            max-width: 400px;
            padding: 15px 15px 15px 160px;
            margin: 2rem 0;
            overflow: hidden;
            font-size: .8125rem;
            line-height: 1.4;
            text-align: left;
            background-color: var(--bs-tertiary-bg)
        }

        #carbonads a {
            color: var(--bs-body-color);
            text-decoration: none
        }

        @media (min-width: 576px) {
            #carbonads {
                border-radius: .5rem
            }
        }

        .carbon-img {
            float: left;
            margin-left: -145px
        }

        .carbon-poweredby {
            display: block;
            margin-top: .75rem;
            color: var(--bs-body-color) !important
        }

        .bd-content>h2,
        .bd-content>h3,
        .bd-content>h4 {
            --bs-heading-color: var(--bs-emphasis-color)
        }

        .bd-content>h2:not(:first-child) {
            margin-top: 3rem
        }

        .bd-content>h3 {
            margin-top: 2rem
        }

        .bd-content>ul li,
        .bd-content>ol li {
            margin-bottom: .25rem
        }

        .bd-content>ul li>p~ul,
        .bd-content>ol li>p~ul {
            margin-top: -.5rem;
            margin-bottom: 1rem
        }

        .bd-content>.table,
        .bd-content>.table-responsive .table {
            --bs-table-border-color: var(--bs-border-color);
            max-width: 100%;
            margin-bottom: 1.5rem;
            font-size: .875rem
        }

        @media (max-width: 991.98px) {

            .bd-content>.table.table-bordered,
            .bd-content>.table-responsive .table.table-bordered {
                border: 0
            }
        }

        .bd-content>.table thead,
        .bd-content>.table-responsive .table thead {
            border-bottom: 2px solid currentcolor
        }

        .bd-content>.table tbody:not(:first-child),
        .bd-content>.table-responsive .table tbody:not(:first-child) {
            border-top: 2px solid currentcolor
        }

        .bd-content>.table th:first-child,
        .bd-content>.table td:first-child,
        .bd-content>.table-responsive .table th:first-child,
        .bd-content>.table-responsive .table td:first-child {
            padding-left: 0
        }

        .bd-content>.table th:not(:last-child),
        .bd-content>.table td:not(:last-child),
        .bd-content>.table-responsive .table th:not(:last-child),
        .bd-content>.table-responsive .table td:not(:last-child) {
            padding-right: 1.5rem
        }

        .bd-content>.table th,
        .bd-content>.table-responsive .table th {
            color: var(--bs-emphasis-color)
        }

        .bd-content>.table strong,
        .bd-content>.table-responsive .table strong {
            color: var(--bs-emphasis-color)
        }

        .bd-content>.table th,
        .bd-content>.table td:first-child>code,
        .bd-content>.table-responsive .table th,
        .bd-content>.table-responsive .table td:first-child>code {
            white-space: nowrap
        }

        .table-options td:nth-child(2) {
            min-width: 160px
        }

        .table-options td:last-child,
        .table-utilities td:last-child {
            min-width: 280px
        }

        .table-swatches th {
            color: var(--bs-emphasis-color)
        }

        .table-swatches td code {
            white-space: nowrap
        }

        .bd-title {
            --bs-heading-color: var(--bs-emphasis-color);
            font-size: calc(1.425rem + 2.1vw)
        }

        @media (min-width: 1200px) {
            .bd-title {
                font-size: 3rem
            }
        }

        .bd-lead {
            font-size: calc(1.275rem + .3vw);
            font-weight: 300
        }

        @media (min-width: 1200px) {
            .bd-lead {
                font-size: 1.5rem
            }
        }

        .bi {
            width: 1em;
            height: 1em;
            vertical-align: -.125em;
            fill: currentcolor
        }

        @media (min-width: 992px) {
            .border-lg-start {
                border-left: var(--bs-border-width) solid var(--bs-border-color)
            }
        }

        .bd-summary-link {
            color: var(--bs-link-color)
        }

        .bd-summary-link:hover,
        details[open]>.bd-summary-link {
            color: var(--bs-link-hover-color)
        }

        [data-bs-theme="blue"] {
            --bs-body-color: var(--bs-white);
            --bs-body-color-rgb: 255, 255, 255;
            --bs-body-bg: var(--bs-blue);
            --bs-body-bg-rgb: 13, 110, 253;
            --bs-tertiary-bg: #0a58ca
        }

        [data-bs-theme="blue"] .dropdown-menu {
            --bs-dropdown-bg: #0c63e4;
            --bs-dropdown-link-active-bg: #084298
        }

        [data-bs-theme="blue"] .btn-secondary {
            --bs-btn-bg: #3d8bfc;
            --bs-btn-border-color: rgba(255, 255, 255, 0.25);
            --bs-btn-hover-bg: #247cfc;
            --bs-btn-hover-border-color: rgba(255, 255, 255, 0.25);
            --bs-btn-active-bg: #0b6dfb;
            --bs-btn-active-border-color: rgba(255, 255, 255, 0.5);
            --bs-btn-focus-border-color: rgba(255, 255, 255, 0.5);
            --bs-btn-focus-box-shadow: 0 0 0 .25rem rgba(255, 255, 255, .2)
        }

        .skippy {
            background-color: #4c0bce
        }

        .skippy a {
            color: #fff
        }

        @media (min-width: 992px) {
            .bd-sidebar {
                position: -webkit-sticky;
                position: sticky;
                top: 5rem;
                display: block !important;
                height: calc(100vh - 6rem);
                padding-left: .25rem;
                margin-left: -.25rem;
                overflow-y: auto
            }
        }

        @media (max-width: 991.98px) {
            .bd-sidebar .offcanvas-lg {
                border-right-color: var(--bs-border-color);
                box-shadow: 0 1rem 3rem rgba(0, 0, 0, 0.175)
            }
        }

        .bd-links-heading {
            color: var(--bs-emphasis-color)
        }

        @media (max-width: 991.98px) {
            .bd-links-nav {
                font-size: .875rem
            }
        }

        @media (max-width: 991.98px) {
            .bd-links-nav {
                -moz-column-count: 2;
                column-count: 2;
                -moz-column-gap: 1.5rem;
                column-gap: 1.5rem
            }

            .bd-links-nav .bd-links-group {
                -moz-column-break-inside: avoid;
                break-inside: avoid
            }

            .bd-links-nav .bd-links-span-all {
                -moz-column-span: all;
                column-span: all
            }
        }

        .bd-links-link {
            padding: .1875rem .5rem;
            margin-top: .125rem;
            margin-left: 1.125rem;
            color: var(--bs-body-color);
            text-decoration: none
        }

        .bd-links-link:hover,
        .bd-links-link:focus,
        .bd-links-link.active {
            color: var(--bs-emphasis-color);
            background-color: var(--bd-sidebar-link-bg)
        }

        .bd-links-link.active {
            font-weight: 600
        }

        .bd-gutter {
            --bs-gutter-x: 3rem
        }

        @media (min-width: 992px) {
            .bd-layout {
                display: grid;
                grid-template-areas: "sidebar main";
                grid-template-columns: 1fr 5fr;
                gap: 1.5rem
            }
        }

        .bd-sidebar {
            grid-area: sidebar
        }

        .bd-main {
            grid-area: main
        }

        @media (max-width: 991.98px) {
            .bd-main {
                max-width: 760px;
                margin-inline: auto
            }
        }

        @media (min-width: 768px) {
            .bd-main {
                display: grid;
                grid-template-areas: "intro" "toc" "content";
                grid-template-rows: auto auto 1fr;
                gap: inherit
            }
        }

        @media (min-width: 992px) {
            .bd-main {
                grid-template-areas: "intro   toc" "content toc";
                grid-template-rows: auto 1fr;
                grid-template-columns: 4fr 1fr
            }
        }

        .bd-intro {
            grid-area: intro
        }

        .bd-toc {
            grid-area: toc
        }

        .bd-content {
            grid-area: content;
            min-width: 1px
        }

        @media (min-width: 992px) {
            .bd-toc {
                position: -webkit-sticky;
                position: sticky;
                top: 5rem;
                right: 0;
                z-index: 2;
                height: calc(100vh - 7rem);
                overflow-y: auto
            }
        }

        .bd-toc nav {
            font-size: .875rem
        }

        .bd-toc nav ul {
            padding-left: 0;
            margin-bottom: 0;
            list-style: none
        }

        .bd-toc nav ul ul {
            padding-left: 1rem
        }

        .bd-toc nav a {
            display: block;
            padding: .125rem 0 .125rem .75rem;
            color: inherit;
            text-decoration: none;
            border-left: .125rem solid transparent
        }

        .bd-toc nav a:hover,
        .bd-toc nav a.active {
            color: var(--bd-toc-color);
            border-left-color: var(--bd-toc-color)
        }

        .bd-toc nav a.active {
            font-weight: 500
        }

        .bd-toc nav a code {
            font: inherit
        }

        .bd-toc-toggle {
            display: flex;
            align-items: center
        }

        @media (max-width: 575.98px) {
            .bd-toc-toggle {
                justify-content: space-between;
                width: 100%
            }
        }

        @media (max-width: 767.98px) {
            .bd-toc-toggle {
                color: var(--bs-body-color);
                border: 1px solid var(--bs-border-color);
                border-radius: var(--bs-border-radius)
            }

            .bd-toc-toggle:hover,
            .bd-toc-toggle:focus,
            .bd-toc-toggle:active,
            .bd-toc-toggle[aria-expanded="true"] {
                color: var(--bd-violet);
                background-color: var(--bs-body-bg);
                border-color: var(--bd-violet)
            }

            .bd-toc-toggle:focus,
            .bd-toc-toggle[aria-expanded="true"] {
                box-shadow: 0 0 0 3px rgba(var(--bd-violet-rgb), 0.25)
            }
        }

        @media (max-width: 767.98px) {
            .bd-toc-collapse nav {
                padding: 1.25rem 1.25rem 1.25rem 1rem;
                background-color: var(--bs-tertiary-bg);
                border: 1px solid var(--bs-border-color);
                border-radius: var(--bs-border-radius)
            }
        }

        @media (min-width: 768px) {
            .bd-toc-collapse {
                display: block !important
            }
        }

        .bd-footer a {
            color: var(--bs-body-color);
            text-decoration: none
        }

        .bd-footer a:hover,
        .bd-footer a:focus {
            color: var(--bs-link-hover-color);
            text-decoration: underline
        }

        .bd-code-snippet {
            margin: 0 -1.5rem 1rem;
            border: solid var(--bs-border-color);
            border-width: 1px 0
        }

        @media (min-width: 768px) {
            .bd-code-snippet {
                margin-right: 0;
                margin-left: 0;
                border-width: 1px;
                border-radius: var(--bs-border-radius)
            }
        }

        .bd-example {
            --bd-example-padding: 1rem;
            position: relative;
            padding: var(--bd-example-padding);
            margin: 0 -1.5rem 1rem;
            border: solid var(--bs-border-color);
            border-width: 1px 0
        }

        .bd-example::after {
            display: block;
            clear: both;
            content: ""
        }

        @media (min-width: 768px) {
            .bd-example {
                --bd-example-padding: 1.5rem;
                margin-right: 0;
                margin-left: 0;
                border-width: 1px;
                border-radius: var(--bs-border-radius)
            }
        }

        .bd-example+p {
            margin-top: 2rem
        }

        .bd-example>.form-control+.form-control {
            margin-top: .5rem
        }

        .bd-example>.nav+.nav,
        .bd-example>.alert+.alert,
        .bd-example>.navbar+.navbar,
        .bd-example>.progress+.progress {
            margin-top: 1rem
        }

        .bd-example>.dropdown-menu {
            position: static;
            display: block
        }

        .bd-example>:last-child,
        .bd-example>nav:last-child .breadcrumb {
            margin-bottom: 0
        }

        .bd-example>hr:last-child {
            margin-bottom: 1rem
        }

        .bd-example>svg+svg,
        .bd-example>img+img {
            margin-left: .5rem
        }

        .bd-example>.btn,
        .bd-example>.btn-group {
            margin: .25rem .125rem
        }

        .bd-example>.btn-toolbar+.btn-toolbar {
            margin-top: .5rem
        }

        .bd-example>.list-group {
            max-width: 400px
        }

        .bd-example>[class*="list-group-horizontal"] {
            max-width: 100%
        }

        .bd-example .fixed-top,
        .bd-example .sticky-top {
            position: static;
            margin: calc(var(--bd-example-padding) * -1) calc(var(--bd-example-padding) * -1) var(--bd-example-padding)
        }

        .bd-example .fixed-bottom,
        .bd-example .sticky-bottom {
            position: static;
            margin: var(--bd-example-padding) calc(var(--bd-example-padding) * -1) calc(var(--bd-example-padding) * -1)
        }

        .bd-example .pagination {
            margin-bottom: 0
        }

        .bd-example-row [class^="col"],
        .bd-example-cols [class^="col"]>*,
        .bd-example-cssgrid [class*="grid"]>* {
            padding-top: .75rem;
            padding-bottom: .75rem;
            background-color: rgba(var(--bd-violet-rgb), 0.15);
            border: 1px solid rgba(var(--bd-violet-rgb), 0.3)
        }

        .bd-example-row .row+.row,
        .bd-example-cssgrid .grid+.grid {
            margin-top: 1rem
        }

        .bd-example-row-flex-cols .row {
            min-height: 10rem;
            background-color: rgba(var(--bd-violet-rgb), 0.15)
        }

        .bd-example-flex div:not(.vr) {
            background-color: rgba(var(--bd-violet-rgb), 0.15);
            border: 1px solid rgba(var(--bd-violet-rgb), 0.3)
        }

        .example-container {
            width: 800px;
            --bs-gutter-x: 1.5rem;
            --bs-gutter-y: 0;
            width: 100%;
            padding-right: calc(var(--bs-gutter-x) * .5);
            padding-left: calc(var(--bs-gutter-x) * .5);
            margin-right: auto;
            margin-left: auto
        }

        .example-row {
            --bs-gutter-x: 1.5rem;
            --bs-gutter-y: 0;
            display: flex;
            flex-wrap: wrap;
            margin-top: calc(-1 * var(--bs-gutter-y));
            margin-right: calc(-.5 * var(--bs-gutter-x));
            margin-left: calc(-.5 * var(--bs-gutter-x))
        }

        .example-content-main {
            flex-shrink: 0;
            width: 100%;
            max-width: 100%;
            padding-right: calc(var(--bs-gutter-x) * .5);
            padding-left: calc(var(--bs-gutter-x) * .5);
            margin-top: var(--bs-gutter-y)
        }

        @media (min-width: 576px) {
            .example-content-main {
                flex: 0 0 auto;
                width: 50%
            }
        }

        @media (min-width: 992px) {
            .example-content-main {
                flex: 0 0 auto;
                width: 66.666667%
            }
        }

        .example-content-secondary {
            flex-shrink: 0;
            width: 100%;
            max-width: 100%;
            padding-right: calc(var(--bs-gutter-x) * .5);
            padding-left: calc(var(--bs-gutter-x) * .5);
            margin-top: var(--bs-gutter-y)
        }

        @media (min-width: 576px) {
            .example-content-secondary {
                flex: 0 0 auto;
                width: 50%
            }
        }

        @media (min-width: 992px) {
            .example-content-secondary {
                flex: 0 0 auto;
                width: 33.333333%
            }
        }

        .bd-example-ratios .ratio {
            display: inline-block;
            width: 10rem;
            color: var(--bs-secondary-color);
            background-color: var(--bs-tertiary-bg);
            border: var(--bs-border-width) solid var(--bs-border-color)
        }

        .bd-example-ratios .ratio>div {
            display: flex;
            align-items: center;
            justify-content: center
        }

        .bd-example-ratios-breakpoint .ratio-4x3 {
            width: 16rem
        }

        @media (min-width: 768px) {
            .bd-example-ratios-breakpoint .ratio-4x3 {
                --bs-aspect-ratio: 50%
            }
        }

        .bd-example-offcanvas .offcanvas {
            position: static;
            display: block;
            height: 200px;
            visibility: visible;
            transform: translate(0)
        }

        .tooltip-demo a {
            white-space: nowrap
        }

        .tooltip-demo .btn {
            margin: .25rem .125rem
        }

        .custom-tooltip {
            --bs-tooltip-bg: var(--bd-violet-bg);
            --bs-tooltip-color: var(--bs-white)
        }

        .custom-popover {
            --bs-popover-max-width: 200px;
            --bs-popover-border-color: var(--bd-violet-bg);
            --bs-popover-header-bg: var(--bd-violet-bg);
            --bs-popover-header-color: var(--bs-white);
            --bs-popover-body-padding-x: 1rem;
            --bs-popover-body-padding-y: .5rem
        }

        .scrollspy-example {
            height: 200px;
            margin-top: .5rem;
            overflow: auto
        }

        .scrollspy-example-2 {
            height: 350px;
            overflow: auto
        }

        .simple-list-example-scrollspy .active {
            background-color: rgba(var(--bd-violet-rgb), 0.15)
        }

        .bd-example-border-utils [class^="border"] {
            display: inline-block;
            width: 5rem;
            height: 5rem;
            margin: .25rem;
            background-color: var(--bs-tertiary-bg)
        }

        .bd-example-rounded-utils [class*="rounded"] {
            margin: .25rem
        }

        .bd-example-position-utils {
            position: relative;
            padding: 2rem
        }

        .bd-example-position-utils .position-relative {
            height: 200px;
            background-color: var(--bs-tertiary-bg)
        }

        .bd-example-position-utils .position-absolute {
            width: 2rem;
            height: 2rem;
            background-color: var(--bs-body-color);
            border-radius: .375rem
        }

        .bd-example-position-examples::after {
            content: none
        }

        .bd-example-placeholder-cards::after {
            display: none
        }

        .bd-example-placeholder-cards .card {
            width: 18rem
        }

        .bd-example-toasts {
            min-height: 240px
        }

        .bd-example-zindex-levels {
            min-height: 15rem
        }

        .bd-example-zindex-levels>div {
            color: var(--bs-body-bg);
            background-color: var(--bd-violet);
            border: 1px solid var(--bd-purple)
        }

        .bd-example-zindex-levels>div>span {
            position: absolute;
            right: 5px;
            bottom: 0
        }

        .bd-example-zindex-levels>:nth-child(2) {
            top: 3rem;
            left: 3rem
        }

        .bd-example-zindex-levels>:nth-child(3) {
            top: 4.5rem;
            left: 4.5rem
        }

        .bd-example-zindex-levels>:nth-child(4) {
            top: 6rem;
            left: 6rem
        }

        .bd-example-zindex-levels>:nth-child(5) {
            top: 7.5rem;
            left: 7.5rem
        }

        .highlight {
            position: relative;
            padding: 0.75rem 1.5rem;
            background-color: var(--bd-pre-bg)
        }

        @media (min-width: 768px) {
            .highlight {
                padding: .75rem 1.25rem;
                border-radius: calc(var(--bs-border-radius) - 1px)
            }
        }

        @media (min-width: 992px) {
            .highlight pre {
                margin-right: 1.875rem
            }
        }

        .highlight pre {
            padding: .25rem 0 .875rem;
            margin-top: .8125rem;
            margin-bottom: 0;
            overflow: overlay;
            white-space: pre;
            background-color: transparent;
            border: 0
        }

        .highlight pre code {
            font-size: inherit;
            color: var(--bs-body-color);
            word-wrap: normal
        }

        .highlight-toolbar {
            background-color: var(--bd-pre-bg)
        }

        .highlight-toolbar+.highlight {
            border-top-left-radius: 0;
            border-top-right-radius: 0
        }

        @media (min-width: 768px) {
            .bd-file-ref .highlight-toolbar {
                border-top-left-radius: calc(var(--bs-border-radius) - 1px);
                border-top-right-radius: calc(var(--bs-border-radius) - 1px)
            }
        }

        .bd-content .bd-code-snippet {
            margin-bottom: 1rem
        }

        .btn-bd-primary {
            --bs-btn-font-weight: 600;
            --bs-btn-color: var(--bs-white);
            --bs-btn-bg: var(--bd-violet-bg);
            --bs-btn-border-color: var(--bd-violet-bg);
            --bs-btn-hover-color: var(--bs-white);
            --bs-btn-hover-bg: #6528e0;
            --bs-btn-hover-border-color: #6528e0;
            --bs-btn-focus-shadow-rgb: var(--bd-violet-rgb);
            --bs-btn-active-color: var(--bs-btn-hover-color);
            --bs-btn-active-bg: #5a23c8;
            --bs-btn-active-border-color: #5a23c8
        }

        .btn-bd-accent {
            --bs-btn-font-weight: 600;
            --bs-btn-color: var(--bd-accent);
            --bs-btn-border-color: var(--bd-accent);
            --bs-btn-hover-color: var(--bd-dark);
            --bs-btn-hover-bg: var(--bd-accent);
            --bs-btn-hover-border-color: var(--bd-accent);
            --bs-btn-focus-shadow-rgb: var(--bd-accent-rgb);
            --bs-btn-active-color: var(--bs-btn-hover-color);
            --bs-btn-active-bg: var(--bs-btn-hover-bg);
            --bs-btn-active-border-color: var(--bs-btn-hover-border-color)
        }

        .btn-bd-light {
            --btn-custom-color: #9461fb;
            --bs-btn-color: var(--bs-gray-600);
            --bs-btn-border-color: var(--bs-border-color);
            --bs-btn-hover-color: var(--btn-custom-color);
            --bs-btn-hover-border-color: var(--btn-custom-color);
            --bs-btn-active-color: var(--btn-custom-color);
            --bs-btn-active-bg: var(--bs-white);
            --bs-btn-active-border-color: var(--btn-custom-color);
            --bs-btn-focus-border-color: var(--btn-custom-color);
            --bs-btn-focus-shadow-rgb: var(--bd-violet-rgb)
        }

        .bd-btn-lg {
            --bs-btn-border-radius: .5rem;
            padding: .8125rem 2rem
        }

        .bd-callout {
            --bs-link-color-rgb: var(--bd-callout-link);
            --bs-code-color: var(--bd-callout-code-color);
            padding: 1.25rem;
            margin-top: 1.25rem;
            margin-bottom: 1.25rem;
            color: var(--bd-callout-color, inherit);
            background-color: var(--bd-callout-bg, var(--bs-gray-100));
            border-left: 0.25rem solid var(--bd-callout-border, var(--bs-gray-300))
        }

        .bd-callout h4 {
            margin-bottom: .25rem
        }

        .bd-callout>:last-child {
            margin-bottom: 0
        }

        .bd-callout+.bd-callout {
            margin-top: -.25rem
        }

        .bd-callout .highlight {
            background-color: rgba(0, 0, 0, 0.05)
        }

        .bd-callout-info {
            --bd-callout-color: var(--bs-info-text-emphasis);
            --bd-callout-bg: var(--bs-info-bg-subtle);
            --bd-callout-border: var(--bs-info-border-subtle)
        }

        .bd-callout-warning {
            --bd-callout-color: var(--bs-warning-text-emphasis);
            --bd-callout-bg: var(--bs-warning-bg-subtle);
            --bd-callout-border: var(--bs-warning-border-subtle)
        }

        .bd-callout-danger {
            --bd-callout-color: var(--bs-danger-text-emphasis);
            --bd-callout-bg: var(--bs-danger-bg-subtle);
            --bd-callout-border: var(--bs-danger-border-subtle)
        }

        .bd-brand-logos {
            color: #712cf9
        }

        .bd-brand-logos .inverse {
            color: #fff;
            background-color: #712cf9
        }

        .bd-brand-item+.bd-brand-item {
            border-top: 1px solid var(--bs-border-color)
        }

        @media (min-width: 768px) {
            .bd-brand-item+.bd-brand-item {
                border-top: 0;
                border-left: 1px solid var(--bs-border-color)
            }
        }

        .color-swatches {
            margin: 0 -5px
        }

        .color-swatches .bd-purple {
            background-color: #4c0bce
        }

        .color-swatches .bd-purple-light {
            background-color: #d5c1fd
        }

        .color-swatches .bd-purple-lighter {
            background-color: #e5e1ea
        }

        .color-swatches .bd-gray {
            background-color: #f9f9f9
        }

        .color-swatch {
            width: 4rem;
            height: 4rem
        }

        @media (min-width: 768px) {
            .color-swatch {
                width: 6rem;
                height: 6rem
            }
        }

        .swatch-blue {
            color: #fff;
            background-color: #0d6efd
        }

        .swatch-blue::after {
            position: absolute;
            top: 1rem;
            right: 1rem;
            padding-left: 1rem;
            font-size: .75rem;
            line-height: 1.35;
            white-space: pre;
            content: "4.50" "\a" "4.50" "\a" "4.66";
            background-color: #0d6efd;
            background-image: linear-gradient(to bottom, transparent 0.25rem, #fff 0.25rem 0.75rem, transparent 0.75rem 1.25rem, #fff 1.25rem 1.75rem, transparent 1.75rem 2.25rem, #000 2.25rem 2.75rem, transparent 2.75rem);
            background-repeat: no-repeat;
            background-size: .5rem 100%
        }

        .swatch-indigo {
            color: #fff;
            background-color: #6610f2
        }

        .swatch-indigo::after {
            position: absolute;
            top: 1rem;
            right: 1rem;
            padding-left: 1rem;
            font-size: .75rem;
            line-height: 1.35;
            white-space: pre;
            content: "7.18" "\a" "7.18" "\a" "2.92";
            background-color: #6610f2;
            background-image: linear-gradient(to bottom, transparent 0.25rem, #fff 0.25rem 0.75rem, transparent 0.75rem 1.25rem, #fff 1.25rem 1.75rem, transparent 1.75rem 2.25rem, #000 2.25rem 2.75rem, transparent 2.75rem);
            background-repeat: no-repeat;
            background-size: .5rem 100%
        }

        .swatch-purple {
            color: #fff;
            background-color: #6f42c1
        }

        .swatch-purple::after {
            position: absolute;
            top: 1rem;
            right: 1rem;
            padding-left: 1rem;
            font-size: .75rem;
            line-height: 1.35;
            white-space: pre;
            content: "6.51" "\a" "6.51" "\a" "3.22";
            background-color: #6f42c1;
            background-image: linear-gradient(to bottom, transparent 0.25rem, #fff 0.25rem 0.75rem, transparent 0.75rem 1.25rem, #fff 1.25rem 1.75rem, transparent 1.75rem 2.25rem, #000 2.25rem 2.75rem, transparent 2.75rem);
            background-repeat: no-repeat;
            background-size: .5rem 100%
        }

        .swatch-pink {
            color: #fff;
            background-color: #d63384
        }

        .swatch-pink::after {
            position: absolute;
            top: 1rem;
            right: 1rem;
            padding-left: 1rem;
            font-size: .75rem;
            line-height: 1.35;
            white-space: pre;
            content: "4.50" "\a" "4.50" "\a" "4.66";
            background-color: #d63384;
            background-image: linear-gradient(to bottom, transparent 0.25rem, #fff 0.25rem 0.75rem, transparent 0.75rem 1.25rem, #fff 1.25rem 1.75rem, transparent 1.75rem 2.25rem, #000 2.25rem 2.75rem, transparent 2.75rem);
            background-repeat: no-repeat;
            background-size: .5rem 100%
        }

        .swatch-red {
            color: #fff;
            background-color: #dc3545
        }

        .swatch-red::after {
            position: absolute;
            top: 1rem;
            right: 1rem;
            padding-left: 1rem;
            font-size: .75rem;
            line-height: 1.35;
            white-space: pre;
            content: "4.52" "\a" "4.52" "\a" "4.63";
            background-color: #dc3545;
            background-image: linear-gradient(to bottom, transparent 0.25rem, #fff 0.25rem 0.75rem, transparent 0.75rem 1.25rem, #fff 1.25rem 1.75rem, transparent 1.75rem 2.25rem, #000 2.25rem 2.75rem, transparent 2.75rem);
            background-repeat: no-repeat;
            background-size: .5rem 100%
        }

        .swatch-orange {
            color: #000;
            background-color: #fd7e14
        }

        .swatch-orange::after {
            position: absolute;
            top: 1rem;
            right: 1rem;
            padding-left: 1rem;
            font-size: .75rem;
            line-height: 1.35;
            white-space: pre;
            content: "8.17" "\a" "2.57" "\a" "8.17";
            background-color: #fd7e14;
            background-image: linear-gradient(to bottom, transparent 0.25rem, #000 0.25rem 0.75rem, transparent 0.75rem 1.25rem, #fff 1.25rem 1.75rem, transparent 1.75rem 2.25rem, #000 2.25rem 2.75rem, transparent 2.75rem);
            background-repeat: no-repeat;
            background-size: .5rem 100%
        }

        .swatch-yellow {
            color: #000;
            background-color: #ffc107
        }

        .swatch-yellow::after {
            position: absolute;
            top: 1rem;
            right: 1rem;
            padding-left: 1rem;
            font-size: .75rem;
            line-height: 1.35;
            white-space: pre;
            content: "12.8" "\a" "1.63" "\a" "12.8";
            background-color: #ffc107;
            background-image: linear-gradient(to bottom, transparent 0.25rem, #000 0.25rem 0.75rem, transparent 0.75rem 1.25rem, #fff 1.25rem 1.75rem, transparent 1.75rem 2.25rem, #000 2.25rem 2.75rem, transparent 2.75rem);
            background-repeat: no-repeat;
            background-size: .5rem 100%
        }

        .swatch-green {
            color: #fff;
            background-color: #198754
        }

        .swatch-green::after {
            position: absolute;
            top: 1rem;
            right: 1rem;
            padding-left: 1rem;
            font-size: .75rem;
            line-height: 1.35;
            white-space: pre;
            content: "4.53" "\a" "4.53" "\a" "4.63";
            background-color: #198754;
            background-image: linear-gradient(to bottom, transparent 0.25rem, #fff 0.25rem 0.75rem, transparent 0.75rem 1.25rem, #fff 1.25rem 1.75rem, transparent 1.75rem 2.25rem, #000 2.25rem 2.75rem, transparent 2.75rem);
            background-repeat: no-repeat;
            background-size: .5rem 100%
        }

        .swatch-teal {
            color: #000;
            background-color: #20c997
        }

        .swatch-teal::after {
            position: absolute;
            top: 1rem;
            right: 1rem;
            padding-left: 1rem;
            font-size: .75rem;
            line-height: 1.35;
            white-space: pre;
            content: "9.86" "\a" "2.12" "\a" "9.86";
            background-color: #20c997;
            background-image: linear-gradient(to bottom, transparent 0.25rem, #000 0.25rem 0.75rem, transparent 0.75rem 1.25rem, #fff 1.25rem 1.75rem, transparent 1.75rem 2.25rem, #000 2.25rem 2.75rem, transparent 2.75rem);
            background-repeat: no-repeat;
            background-size: .5rem 100%
        }

        .swatch-cyan {
            color: #000;
            background-color: #0dcaf0
        }

        .swatch-cyan::after {
            position: absolute;
            top: 1rem;
            right: 1rem;
            padding-left: 1rem;
            font-size: .75rem;
            line-height: 1.35;
            white-space: pre;
            content: "10.7" "\a" "1.95" "\a" "10.7";
            background-color: #0dcaf0;
            background-image: linear-gradient(to bottom, transparent 0.25rem, #000 0.25rem 0.75rem, transparent 0.75rem 1.25rem, #fff 1.25rem 1.75rem, transparent 1.75rem 2.25rem, #000 2.25rem 2.75rem, transparent 2.75rem);
            background-repeat: no-repeat;
            background-size: .5rem 100%
        }

        .swatch-black {
            color: #fff;
            background-color: #000
        }

        .swatch-black::after {
            position: absolute;
            top: 1rem;
            right: 1rem;
            padding-left: 1rem;
            font-size: .75rem;
            line-height: 1.35;
            white-space: pre;
            content: "21" "\a" "21" "\a" "1";
            background-color: #000;
            background-image: linear-gradient(to bottom, transparent 0.25rem, #fff 0.25rem 0.75rem, transparent 0.75rem 1.25rem, #fff 1.25rem 1.75rem, transparent 1.75rem 2.25rem, #000 2.25rem 2.75rem, transparent 2.75rem);
            background-repeat: no-repeat;
            background-size: .5rem 100%
        }

        .swatch-white {
            color: #000;
            background-color: #fff
        }

        .swatch-white::after {
            position: absolute;
            top: 1rem;
            right: 1rem;
            padding-left: 1rem;
            font-size: .75rem;
            line-height: 1.35;
            white-space: pre;
            content: "21" "\a" "1" "\a" "21";
            background-color: #fff;
            background-image: linear-gradient(to bottom, transparent 0.25rem, #000 0.25rem 0.75rem, transparent 0.75rem 1.25rem, #fff 1.25rem 1.75rem, transparent 1.75rem 2.25rem, #000 2.25rem 2.75rem, transparent 2.75rem);
            background-repeat: no-repeat;
            background-size: .5rem 100%
        }

        .swatch-gray {
            color: #fff;
            background-color: #6c757d
        }

        .swatch-gray::after {
            position: absolute;
            top: 1rem;
            right: 1rem;
            padding-left: 1rem;
            font-size: .75rem;
            line-height: 1.35;
            white-space: pre;
            content: "4.68" "\a" "4.68" "\a" "4.47";
            background-color: #6c757d;
            background-image: linear-gradient(to bottom, transparent 0.25rem, #fff 0.25rem 0.75rem, transparent 0.75rem 1.25rem, #fff 1.25rem 1.75rem, transparent 1.75rem 2.25rem, #000 2.25rem 2.75rem, transparent 2.75rem);
            background-repeat: no-repeat;
            background-size: .5rem 100%
        }

        .swatch-gray-dark {
            color: #fff;
            background-color: #343a40
        }

        .swatch-gray-dark::after {
            position: absolute;
            top: 1rem;
            right: 1rem;
            padding-left: 1rem;
            font-size: .75rem;
            line-height: 1.35;
            white-space: pre;
            content: "11.5" "\a" "11.5" "\a" "1.82";
            background-color: #343a40;
            background-image: linear-gradient(to bottom, transparent 0.25rem, #fff 0.25rem 0.75rem, transparent 0.75rem 1.25rem, #fff 1.25rem 1.75rem, transparent 1.75rem 2.25rem, #000 2.25rem 2.75rem, transparent 2.75rem);
            background-repeat: no-repeat;
            background-size: .5rem 100%
        }

        .swatch-gray-500 {
            color: #000;
            background-color: #adb5bd
        }

        .swatch-gray-500::after {
            position: absolute;
            top: 1rem;
            right: 1rem;
            padding-left: 1rem;
            font-size: .75rem;
            line-height: 1.35;
            white-space: pre;
            content: "10.1" "\a" "2.07" "\a" "10.1";
            background-color: #adb5bd;
            background-image: linear-gradient(to bottom, transparent 0.25rem, #000 0.25rem 0.75rem, transparent 0.75rem 1.25rem, #fff 1.25rem 1.75rem, transparent 1.75rem 2.25rem, #000 2.25rem 2.75rem, transparent 2.75rem);
            background-repeat: no-repeat;
            background-size: .5rem 100%
        }

        .bd-blue-100 {
            color: #000;
            background-color: #cfe2ff
        }

        .bd-blue-200 {
            color: #000;
            background-color: #9ec5fe
        }

        .bd-blue-300 {
            color: #000;
            background-color: #6ea8fe
        }

        .bd-blue-400 {
            color: #000;
            background-color: #3d8bfd
        }

        .bd-blue-500 {
            color: #fff;
            background-color: #0d6efd
        }

        .bd-blue-600 {
            color: #fff;
            background-color: #0a58ca
        }

        .bd-blue-700 {
            color: #fff;
            background-color: #084298
        }

        .bd-blue-800 {
            color: #fff;
            background-color: #052c65
        }

        .bd-blue-900 {
            color: #fff;
            background-color: #031633
        }

        .bd-indigo-100 {
            color: #000;
            background-color: #e0cffc
        }

        .bd-indigo-200 {
            color: #000;
            background-color: #c29ffa
        }

        .bd-indigo-300 {
            color: #000;
            background-color: #a370f7
        }

        .bd-indigo-400 {
            color: #fff;
            background-color: #8540f5
        }

        .bd-indigo-500 {
            color: #fff;
            background-color: #6610f2
        }

        .bd-indigo-600 {
            color: #fff;
            background-color: #520dc2
        }

        .bd-indigo-700 {
            color: #fff;
            background-color: #3d0a91
        }

        .bd-indigo-800 {
            color: #fff;
            background-color: #290661
        }

        .bd-indigo-900 {
            color: #fff;
            background-color: #140330
        }

        .bd-purple-100 {
            color: #000;
            background-color: #e2d9f3
        }

        .bd-purple-200 {
            color: #000;
            background-color: #c5b3e6
        }

        .bd-purple-300 {
            color: #000;
            background-color: #a98eda
        }

        .bd-purple-400 {
            color: #000;
            background-color: #8c68cd
        }

        .bd-purple-500 {
            color: #fff;
            background-color: #6f42c1
        }

        .bd-purple-600 {
            color: #fff;
            background-color: #59359a
        }

        .bd-purple-700 {
            color: #fff;
            background-color: #432874
        }

        .bd-purple-800 {
            color: #fff;
            background-color: #2c1a4d
        }

        .bd-purple-900 {
            color: #fff;
            background-color: #160d27
        }

        .bd-pink-100 {
            color: #000;
            background-color: #f7d6e6
        }

        .bd-pink-200 {
            color: #000;
            background-color: #efadce
        }

        .bd-pink-300 {
            color: #000;
            background-color: #e685b5
        }

        .bd-pink-400 {
            color: #000;
            background-color: #de5c9d
        }

        .bd-pink-500 {
            color: #fff;
            background-color: #d63384
        }

        .bd-pink-600 {
            color: #fff;
            background-color: #ab296a
        }

        .bd-pink-700 {
            color: #fff;
            background-color: #801f4f
        }

        .bd-pink-800 {
            color: #fff;
            background-color: #561435
        }

        .bd-pink-900 {
            color: #fff;
            background-color: #2b0a1a
        }

        .bd-red-100 {
            color: #000;
            background-color: #f8d7da
        }

        .bd-red-200 {
            color: #000;
            background-color: #f1aeb5
        }

        .bd-red-300 {
            color: #000;
            background-color: #ea868f
        }

        .bd-red-400 {
            color: #000;
            background-color: #e35d6a
        }

        .bd-red-500 {
            color: #fff;
            background-color: #dc3545
        }

        .bd-red-600 {
            color: #fff;
            background-color: #b02a37
        }

        .bd-red-700 {
            color: #fff;
            background-color: #842029
        }

        .bd-red-800 {
            color: #fff;
            background-color: #58151c
        }

        .bd-red-900 {
            color: #fff;
            background-color: #2c0b0e
        }

        .bd-orange-100 {
            color: #000;
            background-color: #ffe5d0
        }

        .bd-orange-200 {
            color: #000;
            background-color: #fecba1
        }

        .bd-orange-300 {
            color: #000;
            background-color: #feb272
        }

        .bd-orange-400 {
            color: #000;
            background-color: #fd9843
        }

        .bd-orange-500 {
            color: #000;
            background-color: #fd7e14
        }

        .bd-orange-600 {
            color: #000;
            background-color: #ca6510
        }

        .bd-orange-700 {
            color: #fff;
            background-color: #984c0c
        }

        .bd-orange-800 {
            color: #fff;
            background-color: #653208
        }

        .bd-orange-900 {
            color: #fff;
            background-color: #331904
        }

        .bd-yellow-100 {
            color: #000;
            background-color: #fff3cd
        }

        .bd-yellow-200 {
            color: #000;
            background-color: #ffe69c
        }

        .bd-yellow-300 {
            color: #000;
            background-color: #ffda6a
        }

        .bd-yellow-400 {
            color: #000;
            background-color: #ffcd39
        }

        .bd-yellow-500 {
            color: #000;
            background-color: #ffc107
        }

        .bd-yellow-600 {
            color: #000;
            background-color: #cc9a06
        }

        .bd-yellow-700 {
            color: #000;
            background-color: #997404
        }

        .bd-yellow-800 {
            color: #fff;
            background-color: #664d03
        }

        .bd-yellow-900 {
            color: #fff;
            background-color: #332701
        }

        .bd-green-100 {
            color: #000;
            background-color: #d1e7dd
        }

        .bd-green-200 {
            color: #000;
            background-color: #a3cfbb
        }

        .bd-green-300 {
            color: #000;
            background-color: #75b798
        }

        .bd-green-400 {
            color: #000;
            background-color: #479f76
        }

        .bd-green-500 {
            color: #fff;
            background-color: #198754
        }

        .bd-green-600 {
            color: #fff;
            background-color: #146c43
        }

        .bd-green-700 {
            color: #fff;
            background-color: #0f5132
        }

        .bd-green-800 {
            color: #fff;
            background-color: #0a3622
        }

        .bd-green-900 {
            color: #fff;
            background-color: #051b11
        }

        .bd-teal-100 {
            color: #000;
            background-color: #d2f4ea
        }

        .bd-teal-200 {
            color: #000;
            background-color: #a6e9d5
        }

        .bd-teal-300 {
            color: #000;
            background-color: #79dfc1
        }

        .bd-teal-400 {
            color: #000;
            background-color: #4dd4ac
        }

        .bd-teal-500 {
            color: #000;
            background-color: #20c997
        }

        .bd-teal-600 {
            color: #000;
            background-color: #1aa179
        }

        .bd-teal-700 {
            color: #fff;
            background-color: #13795b
        }

        .bd-teal-800 {
            color: #fff;
            background-color: #0d503c
        }

        .bd-teal-900 {
            color: #fff;
            background-color: #06281e
        }

        .bd-cyan-100 {
            color: #000;
            background-color: #cff4fc
        }

        .bd-cyan-200 {
            color: #000;
            background-color: #9eeaf9
        }

        .bd-cyan-300 {
            color: #000;
            background-color: #6edff6
        }

        .bd-cyan-400 {
            color: #000;
            background-color: #3dd5f3
        }

        .bd-cyan-500 {
            color: #000;
            background-color: #0dcaf0
        }

        .bd-cyan-600 {
            color: #000;
            background-color: #0aa2c0
        }

        .bd-cyan-700 {
            color: #fff;
            background-color: #087990
        }

        .bd-cyan-800 {
            color: #fff;
            background-color: #055160
        }

        .bd-cyan-900 {
            color: #fff;
            background-color: #032830
        }

        .bd-gray-100 {
            color: #000;
            background-color: #f8f9fa
        }

        .bd-gray-200 {
            color: #000;
            background-color: #e9ecef
        }

        .bd-gray-300 {
            color: #000;
            background-color: #dee2e6
        }

        .bd-gray-400 {
            color: #000;
            background-color: #ced4da
        }

        .bd-gray-500 {
            color: #000;
            background-color: #adb5bd
        }

        .bd-gray-600 {
            color: #fff;
            background-color: #6c757d
        }

        .bd-gray-700 {
            color: #fff;
            background-color: #495057
        }

        .bd-gray-800 {
            color: #fff;
            background-color: #343a40
        }

        .bd-gray-900 {
            color: #fff;
            background-color: #212529
        }

        .bd-white {
            color: #000;
            background-color: #fff
        }

        .bd-black {
            color: #fff;
            background-color: #000
        }

        .bd-clipboard,
        .bd-edit {
            position: relative;
            display: none;
            float: right
        }

        .bd-clipboard+.highlight,
        .bd-edit+.highlight {
            margin-top: 0
        }

        @media (min-width: 768px) {

            .bd-clipboard,
            .bd-edit {
                display: block
            }
        }

        .btn-clipboard,
        .btn-edit {
            display: block;
            padding: .5em;
            line-height: 1;
            color: var(--bs-body-color);
            background-color: var(--bd-pre-bg);
            border: 0;
            border-radius: .25rem
        }

        .btn-clipboard:hover,
        .btn-edit:hover {
            color: var(--bs-link-hover-color)
        }

        .btn-clipboard:focus,
        .btn-edit:focus {
            z-index: 3
        }

        .btn-clipboard {
            position: relative;
            z-index: 2;
            margin-top: 1.25rem;
            margin-right: .75rem
        }

        .bd-placeholder-img {
            font-size: 1.125rem;
            -webkit-user-select: none;
            -moz-user-select: none;
            user-select: none;
            text-anchor: middle
        }

        .bd-placeholder-img-lg {
            font-size: calc(1.475rem + 2.7vw)
        }

        @media (min-width: 1200px) {
            .bd-placeholder-img-lg {
                font-size: 3.5rem
            }
        }

        main a,
        main button,
        main h2,
        main h3,
        main h4,
        main [tabindex="0"] {
            scroll-margin-top: 80px;
            scroll-margin-bottom: 100px
        }

        :root,
        [data-bs-theme="light"] {
            --base02: #c8c8fa;
            --base03: #565c64;
            --base04: #666;
            --base05: #333;
            --base06: #fff;
            --base07: #13795b;
            --base08: #c6303e;
            --base09: #087990;
            --base0A: #6f42c1;
            --base0B: #084298;
            --base0C: #084298;
            --base0D: #6f42c1;
            --base0E: #ab296a;
            --base0F: #333
        }

        [data-bs-theme="dark"] {
            --base02: #3e4451;
            --base03: #868e96;
            --base04: #868e96;
            --base05: #abb2bf;
            --base06: #b6bdca;
            --base07: #feb272;
            --base08: #6edff6;
            --base09: #feb272;
            --base0A: #ffe69c;
            --base0B: #79dfc1;
            --base0C: #79dfc1;
            --base0D: #6ea8fe;
            --base0E: #c29ffa;
            --base0F: #ea868f
        }

        [data-bs-theme="dark"] .language-diff .gd {
            color: #e35d6a
        }

        [data-bs-theme="dark"] .language-diff .gi {
            color: #479f76
        }

        .hl {
            background-color: var(--base02)
        }

        .c {
            color: var(--base03)
        }

        .err {
            color: var(--base08)
        }

        .k {
            color: var(--base0E)
        }

        .l {
            color: var(----base09)
        }

        .n {
            color: var(--base08)
        }

        .o {
            color: var(--base05)
        }

        .p {
            color: var(--base05)
        }

        .cm {
            color: var(--base04)
        }

        .cp {
            color: var(--base08)
        }

        .c1 {
            color: var(--base03)
        }

        .cs {
            color: var(--base04)
        }

        .gd {
            color: var(--base08)
        }

        .ge {
            font-style: italic
        }

        .gh {
            font-weight: 600;
            color: var(--base0A)
        }

        .gi {
            color: var(--bs-success)
        }

        .gp {
            font-weight: 600;
            color: var(--base04)
        }

        .gs {
            font-weight: 600
        }

        .gu {
            font-weight: 600;
            color: var(--base0C)
        }

        .kc {
            color: var(--base0E)
        }

        .kd {
            color: var(--base0E)
        }

        .kn {
            color: var(--base0C)
        }

        .kp {
            color: var(--base0E)
        }

        .kr {
            color: var(--base0E)
        }

        .kt {
            color: var(--base0A)
        }

        .ld {
            color: var(--base0C)
        }

        .m {
            color: var(--base09)
        }

        .s {
            color: var(--base0C)
        }

        .na {
            color: var(--base0A)
        }

        .nb {
            color: var(--base05)
        }

        .nc {
            color: var(--base07)
        }

        .no {
            color: var(--base08)
        }

        .nd {
            color: var(--base07)
        }

        .ni {
            color: var(--base08)
        }

        .ne {
            color: var(--base08)
        }

        .nf {
            color: var(--base0B)
        }

        .nl {
            color: var(--base05)
        }

        .nn {
            color: var(--base0A)
        }

        .nx {
            color: var(--base0A)
        }

        .py {
            color: var(--base08)
        }

        .nt {
            color: var(--base08)
        }

        .nv {
            color: var(--base08)
        }

        .ow {
            color: var(--base0C)
        }

        .w {
            color: #fff
        }

        .mf {
            color: var(--base09)
        }

        .mh {
            color: var(--base09)
        }

        .mi {
            color: var(--base09)
        }

        .mo {
            color: var(--base09)
        }

        .sb {
            color: var(--base0C)
        }

        .sc {
            color: #fff
        }

        .sd {
            color: var(--base04)
        }

        .s2 {
            color: var(--base0C)
        }

        .se {
            color: var(--base09)
        }

        .sh {
            color: var(--base0C)
        }

        .si {
            color: var(--base09)
        }

        .sx {
            color: var(--base0C)
        }

        .sr {
            color: var(--base0C)
        }

        .s1 {
            color: var(--base0C)
        }

        .ss {
            color: var(--base0C)
        }

        .bp {
            color: var(--base05)
        }

        .vc {
            color: var(--base08)
        }

        .vg {
            color: var(--base08)
        }

        .vi {
            color: var(--base08)
        }

        .il {
            color: var(--base09)
        }

        .m+.o {
            color: var(--base03)
        }

        .language-sh .c {
            color: var(--base03)
        }

        .chroma .language-bash .line::before,
        .chroma .language-sh .line::before {
            color: var(--base03);
            content: "$ ";
            -webkit-user-select: none;
            -moz-user-select: none;
            user-select: none
        }

        .chroma .language-powershell::before {
            color: var(--base0C);
            content: "PM> ";
            -webkit-user-select: none;
            -moz-user-select: none;
            user-select: none
        }

        .anchor-link {
            padding: 0 .175rem;
            font-weight: 400;
            color: rgba(13, 110, 253, 0.5);
            text-decoration: none;
            opacity: 0;
            transition: color 0.15s ease-in-out, opacity 0.15s ease-in-out
        }

        @media (prefers-reduced-motion: reduce) {
            .anchor-link {
                transition: none
            }
        }

        .anchor-link::after {
            content: "#"
        }

        .anchor-link:focus,
        .anchor-link:hover,
        :hover>.anchor-link,
        :target>.anchor-link {
            color: #0d6efd;
            text-decoration: none;
            opacity: 1
        }

        /**
   * Bootstrap "Journal code" icon
   * @link https://icons.getbootstrap.com/icons/journal-code/
   */
        .bd-heading a::before {
            display: inline-block;
            width: 1em;
            height: 1em;
            margin-right: .25rem;
            content: "";
            background-image: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' fill='%25230d6efd' viewBox='0 0 16 16'%3E%3Cpath d='M4 1h8a2 2 0 0 1 2 2v10a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2h1a1 1 0 0 0 1 1h8a1 1 0 0 0 1-1V3a1 1 0 0 0-1-1H4a1 1 0 0 0-1 1H2a2 2 0 0 1 2-2z'/%3E%3Cpath d='M2 5v-.5a.5.5 0 0 1 1 0V5h.5a.5.5 0 0 1 0 1h-2a.5.5 0 0 1 0-1H2zm0 3v-.5a.5.5 0 0 1 1 0V8h.5a.5.5 0 0 1 0 1h-2a.5.5 0 0 1 0-1H2zm0 3v-.5a.5.5 0 0 1 1 0v.5h.5a.5.5 0 0 1 0 1h-2a.5.5 0 0 1 0-1H2z'/%3E%3Cpath fill-rule='evenodd' d='M8.646 5.646a.5.5 0 0 1 .708 0l2 2a.5.5 0 0 1 0 .708l-2 2a.5.5 0 0 1-.708-.708L10.293 8 8.646 6.354a.5.5 0 0 1 0-.708zm-1.292 0a.5.5 0 0 0-.708 0l-2 2a.5.5 0 0 0 0 .708l2 2a.5.5 0 0 0 .708-.708L5.707 8l1.647-1.646a.5.5 0 0 0 0-.708z'/%3E%3C/svg%3E");
            background-size: 1em;
        }

        /* stylelint-disable-next-line selector-max-universal */
        .bd-heading+div>*+* {
            margin-top: 3rem;
        }

        /* Table of contents */
        .bd-aside a {
            padding: .1875rem .5rem;
            margin-top: .125rem;
            margin-left: .3125rem;
            color: rgba(0, 0, 0, .65);
        }

        .bd-aside a:hover,
        .bd-aside a:focus {
            color: rgba(0, 0, 0, .85);
            background-color: rgba(121, 82, 179, .1);
        }

        .bd-aside .active {
            font-weight: 600;
            color: rgba(0, 0, 0, .85);
        }

        .bd-aside .btn {
            padding: .25rem .5rem;
            font-weight: 600;
            color: rgba(0, 0, 0, .65);
        }

        .bd-aside .btn:hover,
        .bd-aside .btn:focus {
            color: rgba(0, 0, 0, .85);
            background-color: rgba(121, 82, 179, .1);
        }

        .bd-aside .btn:focus {
            box-shadow: 0 0 0 1px rgba(121, 82, 179, .7);
        }

        .bd-aside .btn::before {
            width: 1.25em;
            line-height: 0;
            content: url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' width='16' height='16' viewBox='0 0 16 16'%3e%3cpath fill='none' stroke='rgba%280,0,0,.5%29' stroke-linecap='round' stroke-linejoin='round' stroke-width='2' d='M5 14l6-6-6-6'/%3e%3c/svg%3e");
            transition: transform .35s ease;

            /* rtl:raw:
    transform: rotate(180deg) translateX(-2px);
    */
            transform-origin: .5em 50%;
        }

        .bd-aside .btn[aria-expanded="true"]::before {
            transform: rotate(90deg)
                /* rtl:ignore */
            ;
        }


        /* Examples */
        .scrollspy-example {
            height: 200px;
        }

        [id="modal"] .bd-example .btn,
        [id="buttons"] .bd-example .btn,
        [id="tooltips"] .bd-example .btn,
        [id="popovers"] .bd-example .btn,
        [id="dropdowns"] .bd-example .btn-group,
        [id="dropdowns"] .bd-example .dropdown,
        [id="dropdowns"] .bd-example .dropup,
        [id="dropdowns"] .bd-example .dropend,
        [id="dropdowns"] .bd-example .dropstart {
            margin: 0 1rem 1rem 0;
        }

        /* Layout */
        @media (min-width: 1200px) {
            .bg-body-tertiary {
                display: grid;
                grid-template-rows: auto;
                grid-template-columns: 1fr 4fr 1fr;
                gap: 1rem;
            }

            .bd-header {
                position: fixed;
                top: 0;
                /* rtl:begin:ignore */
                right: 0;
                left: 0;
                /* rtl:end:ignore */
                z-index: 1030;
                grid-column: 1 / span 3;
            }

            .bd-aside,
            .bd-cheatsheet {
                padding-top: 4rem;
            }

            /**
     * 1. Too bad only Firefox supports subgrids ATM
     */
            .bd-cheatsheet,
            .bd-cheatsheet section,
            .bd-cheatsheet article {
                display: inherit;
                /* 1 */
                grid-template-rows: auto;
                grid-template-columns: 1fr 4fr;
                grid-column: 1 / span 2;
                gap: inherit;
                /* 1 */
            }

            .bd-aside {
                grid-area: 1 / 3;
                scroll-margin-top: 4rem;
            }

            .bd-cheatsheet section,
            .bd-cheatsheet section>h2 {
                top: 2rem;
                scroll-margin-top: 2rem;
            }

            .bd-cheatsheet section>h2::before {
                position: absolute;
                /* rtl:begin:ignore */
                top: 0;
                right: 0;
                bottom: -2rem;
                left: 0;
                /* rtl:end:ignore */
                z-index: -1;
                content: "";
                background-image: linear-gradient(to bottom, rgba(255, 255, 255, 1) calc(100% - 3rem), rgba(255, 255, 255, .01));
            }

            .bd-cheatsheet article,
            .bd-cheatsheet .bd-heading {
                top: 8rem;
                scroll-margin-top: 8rem;
            }

            .bd-cheatsheet .bd-heading {
                z-index: 1;
            }
        }

        .dd {
            margin-left: 5px;
        }
        .sad{
         font-weight: 700;
      }
      .note{
        padding: 0.01em 16px;
      margin-top: 16px;
    margin-bottom: 16px;
    background-color: #ffffcc;
    border-left: 6px solid #ffeb3b;
      }
      .sas{
      color: crimson;
    background-color: #f1f1f1;
    padding-left: 4px;
    padding-right: 4px;
    font-size: 110%;
        }
       .bas{
      background-color: white;
        color: black;
       font-weight: 700;
      }
.source {
			margin: 25px auto;
		} 
                .container-fixed {
			max-width: 100%;
			margin: 0 auto;
                
                 
                  
                 
		}
      .sid{
         max-height: 350px;
    max-width: 800px;
       overflow-x: auto;
         border-radius: 10px;
        border: solid 5px #97bce1;
      }
       .id{
         max-height: 500px;
   
       overflow-x: auto;
         border-radius: 10px;
       
      }
      .ide{
         max-height: 200px;
   
       overflow-x: auto;
         border-radius: 10px;
       
      }
         .copbut {
    border-radius: 10px;
    position: absolute;
    /*margin-top: -5px;*/
    
    margin-left:140px;        
}             
   .side{
color: #000!important;
background-color: #fff!important;
padding: 8px 16px!important; 
     
}
.nade{
    background-color: #97bce1;
    border-radius: 5px;
    padding: 0.01em 16px;
    margin: 20px 0;
    box-shadow: 0 2px 4px 0 rgba(0,0,0,0.16),0 2px 10px 0 rgba(0,0,0,0.12)!important;
}
    </style>

    <meta name="viewport" content="width=device-width, initial-scale=1">
    <meta name="description"
        content="const is a keyword that is used to declare a constant variable.">
    <meta name="author" content="javascript,javascript tutorial,learn javascript,javascript for beginners,javascript course,javascript basics,javascript crash course,javascript tutorials,javascript full course,javascript tutorial for beginners,javascript in one video,javascript project,beginner javascript,javascript projects,aprender javascript,learn javascript fast,learn javascript for beginners,javascript course for beginners,javascript projects for beginners,javascript dom">
    <link href="https://drive.google.com/uc?id=1goFc09j7jJkkYnCTvGvj-TKVsMbV2Xrz" rel="stylesheet"/>
<script src="https://cdn.jsdelivr.net/highlight.js/9.9.0/highlight.min.js"></script>
	<script>hljs.initHighlightingOnLoad();</script>

    <meta name="docsearch:language" content="en">
    

    <title>Javascript let</title>

   

   
    <script async='async' src='https://www.googletagmanager.com/gtag/js?id=G-QD9XWWKY4Z'>
<script>
    <script src="https://getbootstrap.com/docs/5.3/assets/js/color-modes.js"></script>

    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@docsearch/css@3">

    <link href="https://getbootstrap.com/docs/5.3/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-4bw+/aepP/YC94hEpVNVgiZdgIC5+VKNBQNGCHeKRQN+PtmoHDEXuppvnDJzQIu9" crossorigin="anonymous">

    <!--<link href="https://getbootstrap.com/docs/5.3/assets/css/docs.css" rel="stylesheet">

    Favicons -touch-icon" href="" sizes="180x180">
    <link rel="icon" href="" sizes="32x32" type="image/png">
    <link rel="icon" href="" sizes="16x16" type="image/png">
    <link rel="manifest" href="/docs/5.3/assets/img/favicons/manifest.json">
    <link rel="mask-icon" href="svg" color="#712cf9">
    <link rel="icon" href="">-->
    <meta name="theme-color" content="#712cf9">
    <link href='https://drive.google.com/uc?id=1QQgZ-emZjHd7OYKh-DygkLwjysif-IA6' rel='icon' type='image/x-icon'/>
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:site" content="@new-poste">
    <meta name="twitter:creator" content="@new-poste">
    <meta name="twitter:title" content="Get started with New Poste">
    <meta name="twitter:description"
        content="New Poste It is an educational platform based on simplifying the principles of self-learning based on the development of programmers.">
    <!--<meta name="twitter:image" content="https://getbootstrap.com/docs/5.3/assets/brand/bootstrap-social.png">-->

    <meta property="og:url" content="https://www.new-poste.info/p/devlopement-tutorials-html-css.html">
    <meta property="og:title" content="Get started with New-poste">
    <meta property="og:description"
        content="New Poste It is an educational platform based on simplifying the principles of self-learning based on the development of programmers.">
    <meta property="og:type" content="article">
   
    <meta property="og:image:type" content="image/png">
    <meta property="og:image:width" content="2000">
    <meta property="og:image:height" content="1000">

    <script defer="" src="https://cdn.usefathom.com/script.js" data-site="ITUSEYJG"></script>

    <script>
        window.ga = window.ga || function () { (ga.q = ga.q || []).push(arguments) }; ga.l = +new Date;
        ga('create', 'UA-146052-10', 'new-poste.info');
        ga('set', 'anonymizeIp', true);
        ga('send', 'pageview');
    </script>
    <script async="" src="https://www.google-analytics.com/analytics.js"></script>


</head>

<body data-bs-spy="scroll" data-bs-target="#TableOfContents">
    <div class="skippy visually-hidden-focusable overflow-hidden">
        <div class="container-xl">
            <a class="d-inline-flex p-2 m-1" href="#content">Skip to main content</a>
            <a class="d-none d-md-inline-flex p-2 m-1" href="#bd-docs-nav">Skip to docs navigation</a>
        </div>
    </div>
    <svg xmlns="http://www.w3.org/2000/svg" class="d-none">
        <symbol id="arrow-right" viewBox="0 0 16 16">
            <path fill-rule="evenodd"
                d="M1 8a.5.5 0 0 1 .5-.5h11.793l-3.147-3.146a.5.5 0 0 1 .708-.708l4 4a.5.5 0 0 1 0 .708l-4 4a.5.5 0 0 1-.708-.708L13.293 8.5H1.5A.5.5 0 0 1 1 8z">
            </path>
        </symbol>
        <symbol id="book-half" viewBox="0 0 16 16">
            <path
                d="M8.5 2.687c.654-.689 1.782-.886 3.112-.752 1.234.124 2.503.523 3.388.893v9.923c-.918-.35-2.107-.692-3.287-.81-1.094-.111-2.278-.039-3.213.492V2.687zM8 1.783C7.015.936 5.587.81 4.287.94c-1.514.153-3.042.672-3.994 1.105A.5.5 0 0 0 0 2.5v11a.5.5 0 0 0 .707.455c.882-.4 2.303-.881 3.68-1.02 1.409-.142 2.59.087 3.223.877a.5.5 0 0 0 .78 0c.633-.79 1.814-1.019 3.222-.877 1.378.139 2.8.62 3.681 1.02A.5.5 0 0 0 16 13.5v-11a.5.5 0 0 0-.293-.455c-.952-.433-2.48-.952-3.994-1.105C10.413.809 8.985.936 8 1.783z">
            </path>
        </symbol>
        <symbol id="box-seam" viewBox="0 0 16 16">
            <path
                d="M8.186 1.113a.5.5 0 0 0-.372 0L1.846 3.5l2.404.961L10.404 2l-2.218-.887zm3.564 1.426L5.596 5 8 5.961 14.154 3.5l-2.404-.961zm3.25 1.7-6.5 2.6v7.922l6.5-2.6V4.24zM7.5 14.762V6.838L1 4.239v7.923l6.5 2.6zM7.443.184a1.5 1.5 0 0 1 1.114 0l7.129 2.852A.5.5 0 0 1 16 3.5v8.662a1 1 0 0 1-.629.928l-7.185 2.874a.5.5 0 0 1-.372 0L.63 13.09a1 1 0 0 1-.63-.928V3.5a.5.5 0 0 1 .314-.464L7.443.184z">
            </path>
        </symbol>
        <symbol id="braces" viewBox="0 0 16 16">
            <path
                d="M2.114 8.063V7.9c1.005-.102 1.497-.615 1.497-1.6V4.503c0-1.094.39-1.538 1.354-1.538h.273V2h-.376C3.25 2 2.49 2.759 2.49 4.352v1.524c0 1.094-.376 1.456-1.49 1.456v1.299c1.114 0 1.49.362 1.49 1.456v1.524c0 1.593.759 2.352 2.372 2.352h.376v-.964h-.273c-.964 0-1.354-.444-1.354-1.538V9.663c0-.984-.492-1.497-1.497-1.6zM13.886 7.9v.163c-1.005.103-1.497.616-1.497 1.6v1.798c0 1.094-.39 1.538-1.354 1.538h-.273v.964h.376c1.613 0 2.372-.759 2.372-2.352v-1.524c0-1.094.376-1.456 1.49-1.456V7.332c-1.114 0-1.49-.362-1.49-1.456V4.352C13.51 2.759 12.75 2 11.138 2h-.376v.964h.273c.964 0 1.354.444 1.354 1.538V6.3c0 .984.492 1.497 1.497 1.6z">
            </path>
        </symbol>
        <symbol id="braces-asterisk" viewBox="0 0 16 16">
            <path fill-rule="evenodd"
                d="M1.114 8.063V7.9c1.005-.102 1.497-.615 1.497-1.6V4.503c0-1.094.39-1.538 1.354-1.538h.273V2h-.376C2.25 2 1.49 2.759 1.49 4.352v1.524c0 1.094-.376 1.456-1.49 1.456v1.299c1.114 0 1.49.362 1.49 1.456v1.524c0 1.593.759 2.352 2.372 2.352h.376v-.964h-.273c-.964 0-1.354-.444-1.354-1.538V9.663c0-.984-.492-1.497-1.497-1.6ZM14.886 7.9v.164c-1.005.103-1.497.616-1.497 1.6v1.798c0 1.094-.39 1.538-1.354 1.538h-.273v.964h.376c1.613 0 2.372-.759 2.372-2.352v-1.524c0-1.094.376-1.456 1.49-1.456v-1.3c-1.114 0-1.49-.362-1.49-1.456V4.352C14.51 2.759 13.75 2 12.138 2h-.376v.964h.273c.964 0 1.354.444 1.354 1.538V6.3c0 .984.492 1.497 1.497 1.6ZM7.5 11.5V9.207l-1.621 1.621-.707-.707L6.792 8.5H4.5v-1h2.293L5.172 5.879l.707-.707L7.5 6.792V4.5h1v2.293l1.621-1.621.707.707L9.208 7.5H11.5v1H9.207l1.621 1.621-.707.707L8.5 9.208V11.5h-1Z">
            </path>
        </symbol>
        <symbol id="check2" viewBox="0 0 16 16">
            <path
                d="M13.854 3.646a.5.5 0 0 1 0 .708l-7 7a.5.5 0 0 1-.708 0l-3.5-3.5a.5.5 0 1 1 .708-.708L6.5 10.293l6.646-6.647a.5.5 0 0 1 .708 0z">
            </path>
        </symbol>
        <symbol id="chevron-expand" viewBox="0 0 16 16">
            <path fill-rule="evenodd"
                d="M3.646 9.146a.5.5 0 0 1 .708 0L8 12.793l3.646-3.647a.5.5 0 0 1 .708.708l-4 4a.5.5 0 0 1-.708 0l-4-4a.5.5 0 0 1 0-.708zm0-2.292a.5.5 0 0 0 .708 0L8 3.207l3.646 3.647a.5.5 0 0 0 .708-.708l-4-4a.5.5 0 0 0-.708 0l-4 4a.5.5 0 0 0 0 .708z">
            </path>
        </symbol>
        <symbol id="circle-half" viewBox="0 0 16 16">
            <path d="M8 15A7 7 0 1 0 8 1v14zm0 1A8 8 0 1 1 8 0a8 8 0 0 1 0 16z"></path>
        </symbol>
        <symbol id="clipboard" viewBox="0 0 16 16">
            <path
                d="M4 1.5H3a2 2 0 0 0-2 2V14a2 2 0 0 0 2 2h10a2 2 0 0 0 2-2V3.5a2 2 0 0 0-2-2h-1v1h1a1 1 0 0 1 1 1V14a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V3.5a1 1 0 0 1 1-1h1v-1z">
            </path>
            <path
                d="M9.5 1a.5.5 0 0 1 .5.5v1a.5.5 0 0 1-.5.5h-3a.5.5 0 0 1-.5-.5v-1a.5.5 0 0 1 .5-.5h3zm-3-1A1.5 1.5 0 0 0 5 1.5v1A1.5 1.5 0 0 0 6.5 4h3A1.5 1.5 0 0 0 11 2.5v-1A1.5 1.5 0 0 0 9.5 0h-3z">
            </path>
        </symbol>
        <symbol id="code" viewBox="0 0 16 16">
            <path
                d="M5.854 4.854a.5.5 0 1 0-.708-.708l-3.5 3.5a.5.5 0 0 0 0 .708l3.5 3.5a.5.5 0 0 0 .708-.708L2.707 8l3.147-3.146zm4.292 0a.5.5 0 0 1 .708-.708l3.5 3.5a.5.5 0 0 1 0 .708l-3.5 3.5a.5.5 0 0 1-.708-.708L13.293 8l-3.147-3.146z">
            </path>
        </symbol>
        <symbol id="file-earmark-richtext" viewBox="0 0 16 16">
            <path
                d="M14 4.5V14a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2V2a2 2 0 0 1 2-2h5.5L14 4.5zm-3 0A1.5 1.5 0 0 1 9.5 3V1H4a1 1 0 0 0-1 1v12a1 1 0 0 0 1 1h8a1 1 0 0 0 1-1V4.5h-2z">
            </path>
            <path
                d="M4.5 12.5A.5.5 0 0 1 5 12h3a.5.5 0 0 1 0 1H5a.5.5 0 0 1-.5-.5zm0-2A.5.5 0 0 1 5 10h6a.5.5 0 0 1 0 1H5a.5.5 0 0 1-.5-.5zm1.639-3.708 1.33.886 1.854-1.855a.25.25 0 0 1 .289-.047l1.888.974V8.5a.5.5 0 0 1-.5.5H5a.5.5 0 0 1-.5-.5V8s1.54-1.274 1.639-1.208zM6.25 6a.75.75 0 1 0 0-1.5.75.75 0 0 0 0 1.5z">
            </path>
        </symbol>
        <symbol id="globe2" viewBox="0 0 16 16">
            <path
                d="M0 8a8 8 0 1 1 16 0A8 8 0 0 1 0 8zm7.5-6.923c-.67.204-1.335.82-1.887 1.855-.143.268-.276.56-.395.872.705.157 1.472.257 2.282.287V1.077zM4.249 3.539c.142-.384.304-.744.481-1.078a6.7 6.7 0 0 1 .597-.933A7.01 7.01 0 0 0 3.051 3.05c.362.184.763.349 1.198.49zM3.509 7.5c.036-1.07.188-2.087.436-3.008a9.124 9.124 0 0 1-1.565-.667A6.964 6.964 0 0 0 1.018 7.5h2.49zm1.4-2.741a12.344 12.344 0 0 0-.4 2.741H7.5V5.091c-.91-.03-1.783-.145-2.591-.332zM8.5 5.09V7.5h2.99a12.342 12.342 0 0 0-.399-2.741c-.808.187-1.681.301-2.591.332zM4.51 8.5c.035.987.176 1.914.399 2.741A13.612 13.612 0 0 1 7.5 10.91V8.5H4.51zm3.99 0v2.409c.91.03 1.783.145 2.591.332.223-.827.364-1.754.4-2.741H8.5zm-3.282 3.696c.12.312.252.604.395.872.552 1.035 1.218 1.65 1.887 1.855V11.91c-.81.03-1.577.13-2.282.287zm.11 2.276a6.696 6.696 0 0 1-.598-.933 8.853 8.853 0 0 1-.481-1.079 8.38 8.38 0 0 0-1.198.49 7.01 7.01 0 0 0 2.276 1.522zm-1.383-2.964A13.36 13.36 0 0 1 3.508 8.5h-2.49a6.963 6.963 0 0 0 1.362 3.675c.47-.258.995-.482 1.565-.667zm6.728 2.964a7.009 7.009 0 0 0 2.275-1.521 8.376 8.376 0 0 0-1.197-.49 8.853 8.853 0 0 1-.481 1.078 6.688 6.688 0 0 1-.597.933zM8.5 11.909v3.014c.67-.204 1.335-.82 1.887-1.855.143-.268.276-.56.395-.872A12.63 12.63 0 0 0 8.5 11.91zm3.555-.401c.57.185 1.095.409 1.565.667A6.963 6.963 0 0 0 14.982 8.5h-2.49a13.36 13.36 0 0 1-.437 3.008zM14.982 7.5a6.963 6.963 0 0 0-1.362-3.675c-.47.258-.995.482-1.565.667.248.92.4 1.938.437 3.008h2.49zM11.27 2.461c.177.334.339.694.482 1.078a8.368 8.368 0 0 0 1.196-.49 7.01 7.01 0 0 0-2.275-1.52c.218.283.418.597.597.932zm-.488 1.343a7.765 7.765 0 0 0-.395-.872C9.835 1.897 9.17 1.282 8.5 1.077V4.09c.81-.03 1.577-.13 2.282-.287z">
            </path>
        </symbol>
        <symbol id="grid-fill" viewBox="0 0 16 16">
            <path
                d="M1 2.5A1.5 1.5 0 0 1 2.5 1h3A1.5 1.5 0 0 1 7 2.5v3A1.5 1.5 0 0 1 5.5 7h-3A1.5 1.5 0 0 1 1 5.5v-3zm8 0A1.5 1.5 0 0 1 10.5 1h3A1.5 1.5 0 0 1 15 2.5v3A1.5 1.5 0 0 1 13.5 7h-3A1.5 1.5 0 0 1 9 5.5v-3zm-8 8A1.5 1.5 0 0 1 2.5 9h3A1.5 1.5 0 0 1 7 10.5v3A1.5 1.5 0 0 1 5.5 15h-3A1.5 1.5 0 0 1 1 13.5v-3zm8 0A1.5 1.5 0 0 1 10.5 9h3a1.5 1.5 0 0 1 1.5 1.5v3a1.5 1.5 0 0 1-1.5 1.5h-3A1.5 1.5 0 0 1 9 13.5v-3z">
            </path>
        </symbol>
        <symbol id="lightning-charge-fill" viewBox="0 0 16 16">
            <path
                d="M11.251.068a.5.5 0 0 1 .227.58L9.677 6.5H13a.5.5 0 0 1 .364.843l-8 8.5a.5.5 0 0 1-.842-.49L6.323 9.5H3a.5.5 0 0 1-.364-.843l8-8.5a.5.5 0 0 1 .615-.09z">
            </path>
        </symbol>
        <symbol id="list" viewBox="0 0 16 16">
            <path fill-rule="evenodd"
                d="M2.5 12a.5.5 0 0 1 .5-.5h10a.5.5 0 0 1 0 1H3a.5.5 0 0 1-.5-.5zm0-4a.5.5 0 0 1 .5-.5h10a.5.5 0 0 1 0 1H3a.5.5 0 0 1-.5-.5zm0-4a.5.5 0 0 1 .5-.5h10a.5.5 0 0 1 0 1H3a.5.5 0 0 1-.5-.5z">
            </path>
        </symbol>
        <symbol id="magic" viewBox="0 0 16 16">
            <path
                d="M9.5 2.672a.5.5 0 1 0 1 0V.843a.5.5 0 0 0-1 0v1.829Zm4.5.035A.5.5 0 0 0 13.293 2L12 3.293a.5.5 0 1 0 .707.707L14 2.707ZM7.293 4A.5.5 0 1 0 8 3.293L6.707 2A.5.5 0 0 0 6 2.707L7.293 4Zm-.621 2.5a.5.5 0 1 0 0-1H4.843a.5.5 0 1 0 0 1h1.829Zm8.485 0a.5.5 0 1 0 0-1h-1.829a.5.5 0 0 0 0 1h1.829ZM13.293 10A.5.5 0 1 0 14 9.293L12.707 8a.5.5 0 1 0-.707.707L13.293 10ZM9.5 11.157a.5.5 0 0 0 1 0V9.328a.5.5 0 0 0-1 0v1.829Zm1.854-5.097a.5.5 0 0 0 0-.706l-.708-.708a.5.5 0 0 0-.707 0L8.646 5.94a.5.5 0 0 0 0 .707l.708.708a.5.5 0 0 0 .707 0l1.293-1.293Zm-3 3a.5.5 0 0 0 0-.706l-.708-.708a.5.5 0 0 0-.707 0L.646 13.94a.5.5 0 0 0 0 .707l.708.708a.5.5 0 0 0 .707 0L8.354 9.06Z">
            </path>
        </symbol>
        <symbol id="menu-button-wide-fill" viewBox="0 0 16 16">
            <path
                d="M1.5 0A1.5 1.5 0 0 0 0 1.5v2A1.5 1.5 0 0 0 1.5 5h13A1.5 1.5 0 0 0 16 3.5v-2A1.5 1.5 0 0 0 14.5 0h-13zm1 2h3a.5.5 0 0 1 0 1h-3a.5.5 0 0 1 0-1zm9.927.427A.25.25 0 0 1 12.604 2h.792a.25.25 0 0 1 .177.427l-.396.396a.25.25 0 0 1-.354 0l-.396-.396zM0 8a2 2 0 0 1 2-2h12a2 2 0 0 1 2 2v5a2 2 0 0 1-2 2H2a2 2 0 0 1-2-2V8zm1 3v2a1 1 0 0 0 1 1h12a1 1 0 0 0 1-1v-2H1zm14-1V8a1 1 0 0 0-1-1H2a1 1 0 0 0-1 1v2h14zM2 8.5a.5.5 0 0 1 .5-.5h9a.5.5 0 0 1 0 1h-9a.5.5 0 0 1-.5-.5zm0 4a.5.5 0 0 1 .5-.5h6a.5.5 0 0 1 0 1h-6a.5.5 0 0 1-.5-.5z">
            </path>
        </symbol>
        <symbol id="moon-stars-fill" viewBox="0 0 16 16">
            <path
                d="M6 .278a.768.768 0 0 1 .08.858 7.208 7.208 0 0 0-.878 3.46c0 4.021 3.278 7.277 7.318 7.277.527 0 1.04-.055 1.533-.16a.787.787 0 0 1 .81.316.733.733 0 0 1-.031.893A8.349 8.349 0 0 1 8.344 16C3.734 16 0 12.286 0 7.71 0 4.266 2.114 1.312 5.124.06A.752.752 0 0 1 6 .278z">
            </path>
            <path
                d="M10.794 3.148a.217.217 0 0 1 .412 0l.387 1.162c.173.518.579.924 1.097 1.097l1.162.387a.217.217 0 0 1 0 .412l-1.162.387a1.734 1.734 0 0 0-1.097 1.097l-.387 1.162a.217.217 0 0 1-.412 0l-.387-1.162A1.734 1.734 0 0 0 9.31 6.593l-1.162-.387a.217.217 0 0 1 0-.412l1.162-.387a1.734 1.734 0 0 0 1.097-1.097l.387-1.162zM13.863.099a.145.145 0 0 1 .274 0l.258.774c.115.346.386.617.732.732l.774.258a.145.145 0 0 1 0 .274l-.774.258a1.156 1.156 0 0 0-.732.732l-.258.774a.145.145 0 0 1-.274 0l-.258-.774a1.156 1.156 0 0 0-.732-.732l-.774-.258a.145.145 0 0 1 0-.274l.774-.258c.346-.115.617-.386.732-.732L13.863.1z">
            </path>
        </symbol>
        <symbol id="palette2" viewBox="0 0 16 16">
            <path
                d="M0 .5A.5.5 0 0 1 .5 0h5a.5.5 0 0 1 .5.5v5.277l4.147-4.131a.5.5 0 0 1 .707 0l3.535 3.536a.5.5 0 0 1 0 .708L10.261 10H15.5a.5.5 0 0 1 .5.5v5a.5.5 0 0 1-.5.5H3a2.99 2.99 0 0 1-2.121-.879A2.99 2.99 0 0 1 0 13.044m6-.21 7.328-7.3-2.829-2.828L6 7.188v5.647zM4.5 13a1.5 1.5 0 1 0-3 0 1.5 1.5 0 0 0 3 0zM15 15v-4H9.258l-4.015 4H15zM0 .5v12.495V.5z">
            </path>
            <path d="M0 12.995V13a3.07 3.07 0 0 0 0-.005z"></path>
        </symbol>
        <symbol id="plugin" viewBox="0 0 16 16">
            <path fill-rule="evenodd"
                d="M1 8a7 7 0 1 1 2.898 5.673c-.167-.121-.216-.406-.002-.62l1.8-1.8a3.5 3.5 0 0 0 4.572-.328l1.414-1.415a.5.5 0 0 0 0-.707l-.707-.707 1.559-1.563a.5.5 0 1 0-.708-.706l-1.559 1.562-1.414-1.414 1.56-1.562a.5.5 0 1 0-.707-.706l-1.56 1.56-.707-.706a.5.5 0 0 0-.707 0L5.318 5.975a3.5 3.5 0 0 0-.328 4.571l-1.8 1.8c-.58.58-.62 1.6.121 2.137A8 8 0 1 0 0 8a.5.5 0 0 0 1 0Z">
            </path>
        </symbol>
        <symbol id="plus" viewBox="0 0 16 16">
            <path
                d="M8 4a.5.5 0 0 1 .5.5v3h3a.5.5 0 0 1 0 1h-3v3a.5.5 0 0 1-1 0v-3h-3a.5.5 0 0 1 0-1h3v-3A.5.5 0 0 1 8 4z">
            </path>
        </symbol>
        <symbol id="sun-fill" viewBox="0 0 16 16">
            <path
                d="M8 12a4 4 0 1 0 0-8 4 4 0 0 0 0 8zM8 0a.5.5 0 0 1 .5.5v2a.5.5 0 0 1-1 0v-2A.5.5 0 0 1 8 0zm0 13a.5.5 0 0 1 .5.5v2a.5.5 0 0 1-1 0v-2A.5.5 0 0 1 8 13zm8-5a.5.5 0 0 1-.5.5h-2a.5.5 0 0 1 0-1h2a.5.5 0 0 1 .5.5zM3 8a.5.5 0 0 1-.5.5h-2a.5.5 0 0 1 0-1h2A.5.5 0 0 1 3 8zm10.657-5.657a.5.5 0 0 1 0 .707l-1.414 1.415a.5.5 0 1 1-.707-.708l1.414-1.414a.5.5 0 0 1 .707 0zm-9.193 9.193a.5.5 0 0 1 0 .707L3.05 13.657a.5.5 0 0 1-.707-.707l1.414-1.414a.5.5 0 0 1 .707 0zm9.193 2.121a.5.5 0 0 1-.707 0l-1.414-1.414a.5.5 0 0 1 .707-.707l1.414 1.414a.5.5 0 0 1 0 .707zM4.464 4.465a.5.5 0 0 1-.707 0L2.343 3.05a.5.5 0 1 1 .707-.707l1.414 1.414a.5.5 0 0 1 0 .708z">
            </path>
        </symbol>
        <symbol id="three-dots" viewBox="0 0 16 16">
            <path
                d="M3 9.5a1.5 1.5 0 1 1 0-3 1.5 1.5 0 0 1 0 3zm5 0a1.5 1.5 0 1 1 0-3 1.5 1.5 0 0 1 0 3zm5 0a1.5 1.5 0 1 1 0-3 1.5 1.5 0 0 1 0 3z">
            </path>
        </symbol>
        <symbol id="tools" viewBox="0 0 16 16">
            <path
                d="M1 0 0 1l2.2 3.081a1 1 0 0 0 .815.419h.07a1 1 0 0 1 .708.293l2.675 2.675-2.617 2.654A3.003 3.003 0 0 0 0 13a3 3 0 1 0 5.878-.851l2.654-2.617.968.968-.305.914a1 1 0 0 0 .242 1.023l3.356 3.356a1 1 0 0 0 1.414 0l1.586-1.586a1 1 0 0 0 0-1.414l-3.356-3.356a1 1 0 0 0-1.023-.242L10.5 9.5l-.96-.96 2.68-2.643A3.005 3.005 0 0 0 16 3c0-.269-.035-.53-.102-.777l-2.14 2.141L12 4l-.364-1.757L13.777.102a3 3 0 0 0-3.675 3.68L7.462 6.46 4.793 3.793a1 1 0 0 1-.293-.707v-.071a1 1 0 0 0-.419-.814L1 0zm9.646 10.646a.5.5 0 0 1 .708 0l3 3a.5.5 0 0 1-.708.708l-3-3a.5.5 0 0 1 0-.708zM3 11l.471.242.529.026.287.445.445.287.026.529L5 13l-.242.471-.026.529-.445.287-.287.445-.529.026L3 15l-.471-.242L2 14.732l-.287-.445L1.268 14l-.026-.529L1 13l.242-.471.026-.529.445-.287.287-.445.529-.026L3 11z">
            </path>
        </symbol>
        <symbol id="ui-radios" viewBox="0 0 16 16">
            <path
                d="M7 2.5a.5.5 0 0 1 .5-.5h7a.5.5 0 0 1 .5.5v1a.5.5 0 0 1-.5.5h-7a.5.5 0 0 1-.5-.5v-1zM0 12a3 3 0 1 1 6 0 3 3 0 0 1-6 0zm7-1.5a.5.5 0 0 1 .5-.5h7a.5.5 0 0 1 .5.5v1a.5.5 0 0 1-.5.5h-7a.5.5 0 0 1-.5-.5v-1zm0-5a.5.5 0 0 1 .5-.5h5a.5.5 0 0 1 0 1h-5a.5.5 0 0 1-.5-.5zm0 8a.5.5 0 0 1 .5-.5h5a.5.5 0 0 1 0 1h-5a.5.5 0 0 1-.5-.5zM3 1a3 3 0 1 0 0 6 3 3 0 0 0 0-6zm0 4.5a1.5 1.5 0 1 1 0-3 1.5 1.5 0 0 1 0 3z">
            </path>
        </symbol>
    </svg>


    <header class="navbar navbar-expand-lg bd-navbar sticky-top">
        <nav class="container-xxl bd-gutter flex-wrap flex-lg-nowrap" aria-label="Main navigation">
            <div class="bd-navbar-toggle">
                <button class="navbar-toggler p-2" type="button" data-bs-toggle="offcanvas" data-bs-target="#bdSidebar"
                    aria-controls="bdSidebar" aria-label="Toggle docs navigation">
                    <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" class="bi" fill="currentColor"
                        viewBox="0 0 16 16">
                        <path fill-rule="evenodd"
                            d="M2.5 11.5A.5.5 0 0 1 3 11h10a.5.5 0 0 1 0 1H3a.5.5 0 0 1-.5-.5zm0-4A.5.5 0 0 1 3 7h10a.5.5 0 0 1 0 1H3a.5.5 0 0 1-.5-.5zm0-4A.5.5 0 0 1 3 3h10a.5.5 0 0 1 0 1H3a.5.5 0 0 1-.5-.5z">
                        </path>
                    </svg>

                    <span class="d-none fs-6 pe-1">Browse</span>
                </button>
            </div>

            <a class="navbar-brand p-0 me-0 me-lg-2" href="/" aria-label="Bootstrap">
                <svg height='43' id='svg1' inkscape:version='1.3-beta (cedbd6c6ff, 2023-05-28)'
                    sodipodi:docname='logo1.svg' version='1.1' viewBox='0 0 100 43' width='100' xml:space='preserve'
                    xmlns='http://www.w3.org/2000/svg' xmlns:inkscape='http://www.inkscape.org/namespaces/inkscape'
                    xmlns:sodipodi='http://sodipodi.sourceforge.net/DTD/sodipodi-0.dtd'
                    xmlns:svg='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink'>
                    <defs id='defs1'>
                        <linearGradient id='swatch60' inkscape:swatch='solid'>
                            <stop id='stop61' offset='0' style='stop-color:#000000;stop-opacity:1;' />
                        </linearGradient>
                        <linearGradient id='swatch47' inkscape:swatch='solid'>
                            <stop id='stop47' offset='0' style='stop-color:#000000;stop-opacity:1;' />
                        </linearGradient><color-profile id='color-profile1' name='sRGB-IEC61966-2.1'
                            xlink:href='../../../../Windows/system32/spool/drivers/color/sRGB%20Color%20Space%20Profile.icm' /><color-profile
                            id='color-profile2' name='Agfa-:-Swop-Standard'
                            xlink:href='../../../../Windows/system32/spool/drivers/color/RSWOP.icm' />
                        <rect height='16.124025' id='rect46' width='132.94417' x='-46.79129' y='9.4847212' />
                        <rect height='16.282104' id='rect45' width='80.778206' x='-45.052425' y='12.646295' />
                        <inkscape:path-effect apply_no_weight='true' apply_with_weight='true' effect='bspline'
                            helper_size='0' id='path-effect21' is_visible='true' lpeversion='1.3' only_selected='false'
                            steps='2' uniform='false' weight='33.333333' /><inkscape:path-effect apply_no_weight='true'
                            apply_with_weight='true' effect='bspline' helper_size='0' id='path-effect19'
                            is_visible='true' lpeversion='1.3' only_selected='false' steps='2' uniform='false'
                            weight='33.333333' /><inkscape:path-effect apply_no_weight='true' apply_with_weight='true'
                            effect='bspline' helper_size='0' id='path-effect17' is_visible='true' lpeversion='1.3'
                            only_selected='false' steps='2' uniform='false' weight='33.333333' /><inkscape:path-effect
                            apply_no_weight='true' apply_with_weight='true' effect='bspline' helper_size='0'
                            id='path-effect16' is_visible='true' lpeversion='1.3' only_selected='false' steps='2'
                            uniform='false' weight='33.333333' />
                        <filter height='1.1661645' id='filter21' inkscape:collect='always'
                            style='color-interpolation-filters:sRGB' width='1.0322228' x='-0.026520189'
                            y='-0.080939876'>
                            <feGaussianBlur id='feGaussianBlur21' inkscape:collect='always'
                                stdDeviation='0.001 0.124' />
                        </filter>
                        <meshgradient gradientUnits='userSpaceOnUse' id='meshgradient63' inkscape:collect='always'
                            x='-45.728516' y='4.7821774'>
                            <meshrow id='meshrow63'>
                                <meshpatch id='meshpatch63'>
                                    <stop id='stop63' path='c 27.3385,0  54.6771,0  82.0156,0'
                                        style='stop-color:#ffffff;stop-opacity:1' />
                                    <stop id='stop64' path='c 0,4.29167  0,8.58333  0,12.875'
                                        style='stop-color:#808080;stop-opacity:1' />
                                    <stop id='stop65' path='c -27.3385,0  -54.6771,0  -82.0156,0'
                                        style='stop-color:#ffffff;stop-opacity:1' />
                                    <stop id='stop66' path='c 0,-4.29167  0,-8.58333  0,-12.875'
                                        style='stop-color:#808080;stop-opacity:1' />
                                </meshpatch>
                            </meshrow>
                        </meshgradient>
                        <meshgradient gradientUnits='userSpaceOnUse' id='meshgradient66' inkscape:collect='always'
                            x='-45.173573' y='16.858828'>
                            <meshrow id='meshrow66'>
                                <meshpatch id='meshpatch66'>
                                    <stop id='stop67' path='c 14.624,0  29.248,0  43.872,0'
                                        style='stop-color:#ffffff;stop-opacity:1' />
                                    <stop id='stop68' path='c 0,3.83095  0,7.6619  0,11.4929'
                                        style='stop-color:#808080;stop-opacity:1' />
                                    <stop id='stop69' path='c -14.624,0  -29.248,0  -43.872,0'
                                        style='stop-color:#ffffff;stop-opacity:1' />
                                    <stop id='stop70' path='c 0,-3.83095  0,-7.6619  0,-11.4929'
                                        style='stop-color:#808080;stop-opacity:1' />
                                </meshpatch>
                            </meshrow>
                        </meshgradient>
                        <meshgradient gradientUnits='userSpaceOnUse' id='meshgradient70' inkscape:collect='always'
                            x='-47.388943' y='-3.389169'>
                            <meshrow id='meshrow70'>
                                <meshpatch id='meshpatch70'>
                                    <stop id='stop71' path='c 23.5506,0  47.1012,0  70.6518,0'
                                        style='stop-color:#ffffff;stop-opacity:1' />
                                    <stop id='stop72' path='c 0,22.9307  0,45.8615  0,68.7922'
                                        style='stop-color:#808080;stop-opacity:1' />
                                    <stop id='stop73' path='c -23.5506,0  -47.1012,0  -70.6518,0'
                                        style='stop-color:#ffffff;stop-opacity:1' />
                                    <stop id='stop74' path='c 0,-22.9307  0,-45.8615  0,-68.7922'
                                        style='stop-color:#808080;stop-opacity:1' />
                                </meshpatch>
                            </meshrow>
                        </meshgradient>
                    </defs>
                    <sodipodi:namedview bordercolor='#000000' borderlayer='false' borderopacity='0.25'
                        guidecolor='#001be5' guidehicolor='#8b8b8b' guidehiopacity='0.49803922' guideopacity='0.6'
                        id='namedview1' inkscape:current-layer='g1' inkscape:cx='44.182992' inkscape:cy='29.95591'
                        inkscape:deskcolor='#d1d1d1' inkscape:lockguides='true' inkscape:pagecheckerboard='true'
                        inkscape:pageopacity='0.0' inkscape:showpageshadow='false' inkscape:window-height='705'
                        inkscape:window-maximized='1' inkscape:window-width='1366' inkscape:window-x='-8'
                        inkscape:window-y='-8' inkscape:zoom='6.3259637' pagecolor='#000000'
                        shape-rendering='crispEdges' showborder='true' showgrid='false' />
                    <g id='g1' inkscape:groupmode='layer' inkscape:label='Image'>
                        <path
                            d='m 22.872524,59.515776 c -62.20965,-42.93512 -62.20965,-42.93512 0,0 z M -40.90482,1.38687 c -0.10873,-0.0036 -0.219446,-1.14e-4 -0.328125,0.0098 -0.869432,0.07904 -1.711303,0.60538 -2.185547,1.738281 -0.474244,1.132901 -0.579994,2.871657 -0.474609,4.847656 0.105384,1.975999 0.4205,4.190386 1.158203,6.640625 0.737703,2.450239 1.897511,5.136234 3.214844,7.033204 1.317332,1.896969 2.79366,3.004102 3.689453,4.505859 0.895793,1.501757 1.210478,3.398127 -0.607422,4.267578 -1.8179,0.869451 -5.768037,0.710814 -7.638672,1.791016 -1.870635,1.080202 -1.660616,3.400325 0.236328,4.585937 1.896945,1.185612 5.480017,1.236826 7.429688,1.869141 1.949671,0.632315 2.264916,1.845773 1.369141,3.189453 -0.895775,1.34368 -3.003469,2.818759 -4.953126,4.583984 -1.949656,1.765225 -3.740964,3.819377 -4.689453,6.375 -0.948489,2.555624 -1.05344,5.611297 -0.710937,6.84961 0.342502,1.238312 1.133469,0.660328 1.976562,-0.367188 0.843094,-1.027516 1.739186,-2.504223 2.898438,-4.164062 1.159251,-1.65984 2.58131,-3.503056 4.16211,-4.925782 1.580799,-1.422725 3.319172,-2.424067 4.373046,-2.740234 1.053875,-0.316167 1.423575,0.05273 2.345704,1.291016 0.922128,1.238285 2.396011,3.34618 4.292968,5.216796 1.896957,1.870617 4.216025,3.502685 5.744141,4.451172 1.528115,0.948488 2.266947,1.212057 2.714844,1.396485 0.447896,0.184427 0.605509,0.289852 0.658203,-3.66211 0.05269,-3.951961 1.67e-4,-11.960647 0.210937,-16.65039 0.210771,-4.689743 0.68496,-6.059245 1.185547,-6.902344 0.500587,-0.843099 1.027588,-1.159945 1.34375,-2.134766 0.316162,-0.97482 0.421666,-2.608111 0.158203,-3.503906 -0.263463,-0.895828 -0.897267,-1.052933 -1.898437,-1.263706 -1.001171,-0.210773 -2.370332,-0.475811 -3.898438,-0.765625 -1.528106,-0.289813 -3.214286,-0.605964 -5.005859,-1.238281 C -33.448454,20.367511 -35.629868,15.744624 -36.752476,10.98648 -37.253064,8.747012 -37.675552,6.427702 -37.965367,4.925933 -38.255182,3.424164 -38.413046,2.739978 -38.939976,2.213042 -39.40104,1.751974 -40.143707,1.411724 -40.90482,1.38687 Z'
                            id='path1' sodipodi:nodetypes='sssssssssssssssssssssssssssssssssssss'
                            style='opacity:0.98;fill:#808080;stroke:url(#meshgradient70);stroke-opacity:1;filter:url(#filter21)'
                            transform='matrix(0,0.46783465,-1.5238425,0,100.43732,22.667014)' />
                        <path
                            d='m -38.414413,27.30165 c 8.085335,-0.909246 7.186778,-5.774026 13.170208,-0.249311 0.974851,0.560677 2.882536,0.622939 3.770716,0.07004 3.768486,-4.838915 12.9884469,-0.239885 19.929556,-0.05462 C -25.55495,13.931775 -33.28537,14.980765 -44.046399,27.511766 Z'
                            id='path1-7'
                            style='opacity:0.98;fill:#808080;stroke:url(#meshgradient66);stroke-opacity:1;filter:url(#filter21)'
                            transform='matrix(2.2433868,0,0,1.3929431,102.21625,3.1531377)' /><text id='text45'
                            style='font-size:16px;line-height:5.66666px;white-space:pre;shape-inside:url(#rect46);opacity:1;fill:#808080;fill-opacity:0.982979;stroke:url(#meshgradient63);stroke-opacity:1'
                            transform='matrix(1.1039273,0,0,1.7147874,57.075712,3.1695034)' xml:space='preserve'>
                            <tspan id='tspan2' x='-46.791016' y='16.91499'>New Poste </tspan>
                        </text>
                    </g>
                    <script id='mesh_polyfill' type='text/javascript'>
                        !function () {
                            const t =& quot; http://www.w3.org/2000/svg&quot;,e=&quot;http://www.w3.org/1999/xlink&quot;,s=&quot;http://www.w3.org/1999/xhtml&quot;,r=2;if(document.createElementNS(t,&quot;meshgradient&quot;).x)return;const n=(t,e,s,r)=&gt;{let n=new x(.5*(e.x+s.x),.5*(e.y+s.y)),o=new x(.5*(t.x+e.x),.5*(t.y+e.y)),i=new x(.5*(s.x+r.x),.5*(s.y+r.y)),a=new x(.5*(n.x+o.x),.5*(n.y+o.y)),h=new x(.5*(n.x+i.x),.5*(n.y+i.y)),l=new x(.5*(a.x+h.x),.5*(a.y+h.y));return[[t,o,a,l],[l,h,i,r]]},o=t=&gt;{let e=t[0].distSquared(t[1]),s=t[2].distSquared(t[3]),r=.25*t[0].distSquared(t[2]),n=.25*t[1].distSquared(t[3]),o=e&gt;s?e:s,i=r&gt;n?r:n;return 18*(o&gt;i?o:i)},i=(t,e)=&gt;Math.sqrt(t.distSquared(e)),a=(t,e)=&gt;t.scale(2/3).add(e.scale(1/3)),h=t=&gt;{let e,s,r,n,o,i,a,h=new g;return t.match(/(\w+\(\s*[^)]+\))+/g).forEach(t=&gt;{let l=t.match(/[\w.-]+/g),d=l.shift();switch(d){case&quot;translate&quot;:2===l.length?e=new g(1,0,0,1,l[0],l[1]):(console.error(&quot;mesh.js: translate does not have 2 arguments!&quot;),e=new g(1,0,0,1,0,0)),h=h.append(e);break;case&quot;scale&quot;:1===l.length?s=new g(l[0],0,0,l[0],0,0):2===l.length?s=new g(l[0],0,0,l[1],0,0):(console.error(&quot;mesh.js: scale does not have 1 or 2 arguments!&quot;),s=new g(1,0,0,1,0,0)),h=h.append(s);break;case&quot;rotate&quot;:if(3===l.length&amp;&amp;(e=new g(1,0,0,1,l[1],l[2]),h=h.append(e)),l[0]){r=l[0]*Math.PI/180;let t=Math.cos(r),e=Math.sin(r);Math.abs(t)&lt;1e-16&amp;&amp;(t=0),Math.abs(e)&lt;1e-16&amp;&amp;(e=0),a=new g(t,e,-e,t,0,0),h=h.append(a)}else console.error(&quot;math.js: No argument to rotate transform!&quot;);3===l.length&amp;&amp;(e=new g(1,0,0,1,-l[1],-l[2]),h=h.append(e));break;case&quot;skewX&quot;:l[0]?(r=l[0]*Math.PI/180,n=Math.tan(r),o=new g(1,0,n,1,0,0),h=h.append(o)):console.error(&quot;math.js: No argument to skewX transform!&quot;);break;case&quot;skewY&quot;:l[0]?(r=l[0]*Math.PI/180,n=Math.tan(r),i=new g(1,n,0,1,0,0),h=h.append(i)):console.error(&quot;math.js: No argument to skewY transform!&quot;);break;case&quot;matrix&quot;:6===l.length?h=h.append(new g(...l)):console.error(&quot;math.js: Incorrect number of arguments for matrix!&quot;);break;default:console.error(&quot;mesh.js: Unhandled transform type: &quot;+d)}}),h},l=t=&gt;{let e=[],s=t.split(/[ ,]+/);for(let t=0,r=s.length-1;t&lt;r;t+=2)e.push(new x(parseFloat(s[t]),parseFloat(s[t+1])));return e},d=(t,e)=&gt;{for(let s in e)t.setAttribute(s,e[s])},c=(t,e,s,r,n)=&gt;{let o,i,a=[0,0,0,0];for(let h=0;h&lt;3;++h)e[h]&lt;t[h]&amp;&amp;e[h]&lt;s[h]||t[h]&lt;e[h]&amp;&amp;s[h]&lt;e[h]?a[h]=0:(a[h]=.5*((e[h]-t[h])/r+(s[h]-e[h])/n),o=Math.abs(3*(e[h]-t[h])/r),i=Math.abs(3*(s[h]-e[h])/n),a[h]&gt;o?a[h]=o:a[h]&gt;i&amp;&amp;(a[h]=i));return a},u=[[1,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0],[0,0,0,0,1,0,0,0,0,0,0,0,0,0,0,0],[-3,3,0,0,-2,-1,0,0,0,0,0,0,0,0,0,0],[2,-2,0,0,1,1,0,0,0,0,0,0,0,0,0,0],[0,0,0,0,0,0,0,0,1,0,0,0,0,0,0,0],[0,0,0,0,0,0,0,0,0,0,0,0,1,0,0,0],[0,0,0,0,0,0,0,0,-3,3,0,0,-2,-1,0,0],[0,0,0,0,0,0,0,0,2,-2,0,0,1,1,0,0],[-3,0,3,0,0,0,0,0,-2,0,-1,0,0,0,0,0],[0,0,0,0,-3,0,3,0,0,0,0,0,-2,0,-1,0],[9,-9,-9,9,6,3,-6,-3,6,-6,3,-3,4,2,2,1],[-6,6,6,-6,-3,-3,3,3,-4,4,-2,2,-2,-2,-1,-1],[2,0,-2,0,0,0,0,0,1,0,1,0,0,0,0,0],[0,0,0,0,2,0,-2,0,0,0,0,0,1,0,1,0],[-6,6,6,-6,-4,-2,4,2,-3,3,-3,3,-2,-1,-2,-1],[4,-4,-4,4,2,2,-2,-2,2,-2,2,-2,1,1,1,1]],f=t=&gt;{let e=[];for(let s=0;s&lt;16;++s){e[s]=0;for(let r=0;r&lt;16;++r)e[s]+=u[s][r]*t[r]}return e},p=(t,e,s)=&gt;{const r=e*e,n=s*s,o=e*e*e,i=s*s*s;return t[0]+t[1]*e+t[2]*r+t[3]*o+t[4]*s+t[5]*s*e+t[6]*s*r+t[7]*s*o+t[8]*n+t[9]*n*e+t[10]*n*r+t[11]*n*o+t[12]*i+t[13]*i*e+t[14]*i*r+t[15]*i*o},y=t=&gt;{let e=[],s=[],r=[];for(let s=0;s&lt;4;++s)e[s]=[],e[s][0]=n(t[0][s],t[1][s],t[2][s],t[3][s]),e[s][1]=[],e[s][1].push(...n(...e[s][0][0])),e[s][1].push(...n(...e[s][0][1])),e[s][2]=[],e[s][2].push(...n(...e[s][1][0])),e[s][2].push(...n(...e[s][1][1])),e[s][2].push(...n(...e[s][1][2])),e[s][2].push(...n(...e[s][1][3]));for(let t=0;t&lt;8;++t){s[t]=[];for(let r=0;r&lt;4;++r)s[t][r]=[],s[t][r][0]=n(e[0][2][t][r],e[1][2][t][r],e[2][2][t][r],e[3][2][t][r]),s[t][r][1]=[],s[t][r][1].push(...n(...s[t][r][0][0])),s[t][r][1].push(...n(...s[t][r][0][1])),s[t][r][2]=[],s[t][r][2].push(...n(...s[t][r][1][0])),s[t][r][2].push(...n(...s[t][r][1][1])),s[t][r][2].push(...n(...s[t][r][1][2])),s[t][r][2].push(...n(...s[t][r][1][3]))}for(let t=0;t&lt;8;++t){r[t]=[];for(let e=0;e&lt;8;++e)r[t][e]=[],r[t][e][0]=s[t][0][2][e],r[t][e][1]=s[t][1][2][e],r[t][e][2]=s[t][2][2][e],r[t][e][3]=s[t][3][2][e]}return r};class x{constructor(t,e){this.x=t||0,this.y=e||0}toString(){return`(x=${this.x}, y=${this.y})`}clone(){return new x(this.x,this.y)}add(t){return new x(this.x+t.x,this.y+t.y)}scale(t){return void 0===t.x?new x(this.x*t,this.y*t):new x(this.x*t.x,this.y*t.y)}distSquared(t){let e=this.x-t.x,s=this.y-t.y;return e*e+s*s}transform(t){let e=this.x*t.a+this.y*t.c+t.e,s=this.x*t.b+this.y*t.d+t.f;return new x(e,s)}}class g{constructor(t,e,s,r,n,o){void 0===t?(this.a=1,this.b=0,this.c=0,this.d=1,this.e=0,this.f=0):(this.a=t,this.b=e,this.c=s,this.d=r,this.e=n,this.f=o)}toString(){return`affine: ${this.a} ${this.c} ${this.e} \n       ${this.b} ${this.d} ${this.f}`}append(t){t instanceof g||console.error(&quot;mesh.js: argument to Affine.append is not affine!&quot;);let e=this.a*t.a+this.c*t.b,s=this.b*t.a+this.d*t.b,r=this.a*t.c+this.c*t.d,n=this.b*t.c+this.d*t.d,o=this.a*t.e+this.c*t.f+this.e,i=this.b*t.e+this.d*t.f+this.f;return new g(e,s,r,n,o,i)}}class w{constructor(t,e){this.nodes=t,this.colors=e}paintCurve(t,e){if(o(this.nodes)&gt;r){const s=n(...this.nodes);let r=[[],[]],o=[[],[]];for(let t=0;t&lt;4;++t)r[0][t]=this.colors[0][t],r[1][t]=(this.colors[0][t]+this.colors[1][t])/2,o[0][t]=r[1][t],o[1][t]=this.colors[1][t];let i=new w(s[0],r),a=new w(s[1],o);i.paintCurve(t,e),a.paintCurve(t,e)}else{let s=Math.round(this.nodes[0].x);if(s&gt;=0&amp;&amp;s&lt;e){let r=4*(~~this.nodes[0].y*e+s);t[r]=Math.round(this.colors[0][0]),t[r+1]=Math.round(this.colors[0][1]),t[r+2]=Math.round(this.colors[0][2]),t[r+3]=Math.round(this.colors[0][3])}}}}class m{constructor(t,e){this.nodes=t,this.colors=e}split(){let t=[[],[],[],[]],e=[[],[],[],[]],s=[[[],[]],[[],[]]],r=[[[],[]],[[],[]]];for(let s=0;s&lt;4;++s){const r=n(this.nodes[0][s],this.nodes[1][s],this.nodes[2][s],this.nodes[3][s]);t[0][s]=r[0][0],t[1][s]=r[0][1],t[2][s]=r[0][2],t[3][s]=r[0][3],e[0][s]=r[1][0],e[1][s]=r[1][1],e[2][s]=r[1][2],e[3][s]=r[1][3]}for(let t=0;t&lt;4;++t)s[0][0][t]=this.colors[0][0][t],s[0][1][t]=this.colors[0][1][t],s[1][0][t]=(this.colors[0][0][t]+this.colors[1][0][t])/2,s[1][1][t]=(this.colors[0][1][t]+this.colors[1][1][t])/2,r[0][0][t]=s[1][0][t],r[0][1][t]=s[1][1][t],r[1][0][t]=this.colors[1][0][t],r[1][1][t]=this.colors[1][1][t];return[new m(t,s),new m(e,r)]}paint(t,e){let s,n=!1;for(let t=0;t&lt;4;++t)if((s=o([this.nodes[0][t],this.nodes[1][t],this.nodes[2][t],this.nodes[3][t]]))&gt;r){n=!0;break}if(n){let s=this.split();s[0].paint(t,e),s[1].paint(t,e)}else{new w([...this.nodes[0]],[...this.colors[0]]).paintCurve(t,e)}}}class b{constructor(t){this.readMesh(t),this.type=t.getAttribute(&quot;type&quot;)||&quot;bilinear&quot;}readMesh(t){let e=[[]],s=[[]],r=Number(t.getAttribute(&quot;x&quot;)),n=Number(t.getAttribute(&quot;y&quot;));e[0][0]=new x(r,n);let o=t.children;for(let t=0,r=o.length;t&lt;r;++t){e[3*t+1]=[],e[3*t+2]=[],e[3*t+3]=[],s[t+1]=[];let r=o[t].children;for(let n=0,o=r.length;n&lt;o;++n){let o=r[n].children;for(let r=0,i=o.length;r&lt;i;++r){let i=r;0!==t&amp;&amp;++i;let h,d=o[r].getAttribute(&quot;path&quot;),c=&quot;l&quot;;null!=d&amp;&amp;(c=(h=d.match(/\s*([lLcC])\s*(.*)/))[1]);let u=l(h[2]);switch(c){case&quot;l&quot;:0===i?(e[3*t][3*n+3]=u[0].add(e[3*t][3*n]),e[3*t][3*n+1]=a(e[3*t][3*n],e[3*t][3*n+3]),e[3*t][3*n+2]=a(e[3*t][3*n+3],e[3*t][3*n])):1===i?(e[3*t+3][3*n+3]=u[0].add(e[3*t][3*n+3]),e[3*t+1][3*n+3]=a(e[3*t][3*n+3],e[3*t+3][3*n+3]),e[3*t+2][3*n+3]=a(e[3*t+3][3*n+3],e[3*t][3*n+3])):2===i?(0===n&amp;&amp;(e[3*t+3][3*n+0]=u[0].add(e[3*t+3][3*n+3])),e[3*t+3][3*n+1]=a(e[3*t+3][3*n],e[3*t+3][3*n+3]),e[3*t+3][3*n+2]=a(e[3*t+3][3*n+3],e[3*t+3][3*n])):(e[3*t+1][3*n]=a(e[3*t][3*n],e[3*t+3][3*n]),e[3*t+2][3*n]=a(e[3*t+3][3*n],e[3*t][3*n]));break;case&quot;L&quot;:0===i?(e[3*t][3*n+3]=u[0],e[3*t][3*n+1]=a(e[3*t][3*n],e[3*t][3*n+3]),e[3*t][3*n+2]=a(e[3*t][3*n+3],e[3*t][3*n])):1===i?(e[3*t+3][3*n+3]=u[0],e[3*t+1][3*n+3]=a(e[3*t][3*n+3],e[3*t+3][3*n+3]),e[3*t+2][3*n+3]=a(e[3*t+3][3*n+3],e[3*t][3*n+3])):2===i?(0===n&amp;&amp;(e[3*t+3][3*n+0]=u[0]),e[3*t+3][3*n+1]=a(e[3*t+3][3*n],e[3*t+3][3*n+3]),e[3*t+3][3*n+2]=a(e[3*t+3][3*n+3],e[3*t+3][3*n])):(e[3*t+1][3*n]=a(e[3*t][3*n],e[3*t+3][3*n]),e[3*t+2][3*n]=a(e[3*t+3][3*n],e[3*t][3*n]));break;case&quot;c&quot;:0===i?(e[3*t][3*n+1]=u[0].add(e[3*t][3*n]),e[3*t][3*n+2]=u[1].add(e[3*t][3*n]),e[3*t][3*n+3]=u[2].add(e[3*t][3*n])):1===i?(e[3*t+1][3*n+3]=u[0].add(e[3*t][3*n+3]),e[3*t+2][3*n+3]=u[1].add(e[3*t][3*n+3]),e[3*t+3][3*n+3]=u[2].add(e[3*t][3*n+3])):2===i?(e[3*t+3][3*n+2]=u[0].add(e[3*t+3][3*n+3]),e[3*t+3][3*n+1]=u[1].add(e[3*t+3][3*n+3]),0===n&amp;&amp;(e[3*t+3][3*n+0]=u[2].add(e[3*t+3][3*n+3]))):(e[3*t+2][3*n]=u[0].add(e[3*t+3][3*n]),e[3*t+1][3*n]=u[1].add(e[3*t+3][3*n]));break;case&quot;C&quot;:0===i?(e[3*t][3*n+1]=u[0],e[3*t][3*n+2]=u[1],e[3*t][3*n+3]=u[2]):1===i?(e[3*t+1][3*n+3]=u[0],e[3*t+2][3*n+3]=u[1],e[3*t+3][3*n+3]=u[2]):2===i?(e[3*t+3][3*n+2]=u[0],e[3*t+3][3*n+1]=u[1],0===n&amp;&amp;(e[3*t+3][3*n+0]=u[2])):(e[3*t+2][3*n]=u[0],e[3*t+1][3*n]=u[1]);break;default:console.error(&quot;mesh.js: &quot;+c+&quot; invalid path type.&quot;)}if(0===t&amp;&amp;0===n||r&gt;0){let e=window.getComputedStyle(o[r]).stopColor.match(/^rgb\s*\(\s*(\d+)\s*,\s*(\d+)\s*,\s*(\d+)\s*\)$/i),a=window.getComputedStyle(o[r]).stopOpacity,h=255;a&amp;&amp;(h=Math.floor(255*a)),e&amp;&amp;(0===i?(s[t][n]=[],s[t][n][0]=Math.floor(e[1]),s[t][n][1]=Math.floor(e[2]),s[t][n][2]=Math.floor(e[3]),s[t][n][3]=h):1===i?(s[t][n+1]=[],s[t][n+1][0]=Math.floor(e[1]),s[t][n+1][1]=Math.floor(e[2]),s[t][n+1][2]=Math.floor(e[3]),s[t][n+1][3]=h):2===i?(s[t+1][n+1]=[],s[t+1][n+1][0]=Math.floor(e[1]),s[t+1][n+1][1]=Math.floor(e[2]),s[t+1][n+1][2]=Math.floor(e[3]),s[t+1][n+1][3]=h):3===i&amp;&amp;(s[t+1][n]=[],s[t+1][n][0]=Math.floor(e[1]),s[t+1][n][1]=Math.floor(e[2]),s[t+1][n][2]=Math.floor(e[3]),s[t+1][n][3]=h))}}e[3*t+1][3*n+1]=new x,e[3*t+1][3*n+2]=new x,e[3*t+2][3*n+1]=new x,e[3*t+2][3*n+2]=new x,e[3*t+1][3*n+1].x=(-4*e[3*t][3*n].x+6*(e[3*t][3*n+1].x+e[3*t+1][3*n].x)+-2*(e[3*t][3*n+3].x+e[3*t+3][3*n].x)+3*(e[3*t+3][3*n+1].x+e[3*t+1][3*n+3].x)+-1*e[3*t+3][3*n+3].x)/9,e[3*t+1][3*n+2].x=(-4*e[3*t][3*n+3].x+6*(e[3*t][3*n+2].x+e[3*t+1][3*n+3].x)+-2*(e[3*t][3*n].x+e[3*t+3][3*n+3].x)+3*(e[3*t+3][3*n+2].x+e[3*t+1][3*n].x)+-1*e[3*t+3][3*n].x)/9,e[3*t+2][3*n+1].x=(-4*e[3*t+3][3*n].x+6*(e[3*t+3][3*n+1].x+e[3*t+2][3*n].x)+-2*(e[3*t+3][3*n+3].x+e[3*t][3*n].x)+3*(e[3*t][3*n+1].x+e[3*t+2][3*n+3].x)+-1*e[3*t][3*n+3].x)/9,e[3*t+2][3*n+2].x=(-4*e[3*t+3][3*n+3].x+6*(e[3*t+3][3*n+2].x+e[3*t+2][3*n+3].x)+-2*(e[3*t+3][3*n].x+e[3*t][3*n+3].x)+3*(e[3*t][3*n+2].x+e[3*t+2][3*n].x)+-1*e[3*t][3*n].x)/9,e[3*t+1][3*n+1].y=(-4*e[3*t][3*n].y+6*(e[3*t][3*n+1].y+e[3*t+1][3*n].y)+-2*(e[3*t][3*n+3].y+e[3*t+3][3*n].y)+3*(e[3*t+3][3*n+1].y+e[3*t+1][3*n+3].y)+-1*e[3*t+3][3*n+3].y)/9,e[3*t+1][3*n+2].y=(-4*e[3*t][3*n+3].y+6*(e[3*t][3*n+2].y+e[3*t+1][3*n+3].y)+-2*(e[3*t][3*n].y+e[3*t+3][3*n+3].y)+3*(e[3*t+3][3*n+2].y+e[3*t+1][3*n].y)+-1*e[3*t+3][3*n].y)/9,e[3*t+2][3*n+1].y=(-4*e[3*t+3][3*n].y+6*(e[3*t+3][3*n+1].y+e[3*t+2][3*n].y)+-2*(e[3*t+3][3*n+3].y+e[3*t][3*n].y)+3*(e[3*t][3*n+1].y+e[3*t+2][3*n+3].y)+-1*e[3*t][3*n+3].y)/9,e[3*t+2][3*n+2].y=(-4*e[3*t+3][3*n+3].y+6*(e[3*t+3][3*n+2].y+e[3*t+2][3*n+3].y)+-2*(e[3*t+3][3*n].y+e[3*t][3*n+3].y)+3*(e[3*t][3*n+2].y+e[3*t+2][3*n].y)+-1*e[3*t][3*n].y)/9}}this.nodes=e,this.colors=s}paintMesh(t,e){let s=(this.nodes.length-1)/3,r=(this.nodes[0].length-1)/3;if(&quot;bilinear&quot;===this.type||s&lt;2||r&lt;2){let n;for(let o=0;o&lt;s;++o)for(let s=0;s&lt;r;++s){let r=[];for(let t=3*o,e=3*o+4;t&lt;e;++t)r.push(this.nodes[t].slice(3*s,3*s+4));let i=[];i.push(this.colors[o].slice(s,s+2)),i.push(this.colors[o+1].slice(s,s+2)),(n=new m(r,i)).paint(t,e)}}else{let n,o,a,h,l,d,u;const x=s,g=r;s++,r++;let w=new Array(s);for(let t=0;t&lt;s;++t){w[t]=new Array(r);for(let e=0;e&lt;r;++e)w[t][e]=[],w[t][e][0]=this.nodes[3*t][3*e],w[t][e][1]=this.colors[t][e]}for(let t=0;t&lt;s;++t)for(let e=0;e&lt;r;++e)0!==t&amp;&amp;t!==x&amp;&amp;(n=i(w[t-1][e][0],w[t][e][0]),o=i(w[t+1][e][0],w[t][e][0]),w[t][e][2]=c(w[t-1][e][1],w[t][e][1],w[t+1][e][1],n,o)),0!==e&amp;&amp;e!==g&amp;&amp;(n=i(w[t][e-1][0],w[t][e][0]),o=i(w[t][e+1][0],w[t][e][0]),w[t][e][3]=c(w[t][e-1][1],w[t][e][1],w[t][e+1][1],n,o));for(let t=0;t&lt;r;++t){w[0][t][2]=[],w[x][t][2]=[];for(let e=0;e&lt;4;++e)n=i(w[1][t][0],w[0][t][0]),o=i(w[x][t][0],w[x-1][t][0]),w[0][t][2][e]=n&gt;0?2*(w[1][t][1][e]-w[0][t][1][e])/n-w[1][t][2][e]:0,w[x][t][2][e]=o&gt;0?2*(w[x][t][1][e]-w[x-1][t][1][e])/o-w[x-1][t][2][e]:0}for(let t=0;t&lt;s;++t){w[t][0][3]=[],w[t][g][3]=[];for(let e=0;e&lt;4;++e)n=i(w[t][1][0],w[t][0][0]),o=i(w[t][g][0],w[t][g-1][0]),w[t][0][3][e]=n&gt;0?2*(w[t][1][1][e]-w[t][0][1][e])/n-w[t][1][3][e]:0,w[t][g][3][e]=o&gt;0?2*(w[t][g][1][e]-w[t][g-1][1][e])/o-w[t][g-1][3][e]:0}for(let s=0;s&lt;x;++s)for(let r=0;r&lt;g;++r){let n=i(w[s][r][0],w[s+1][r][0]),o=i(w[s][r+1][0],w[s+1][r+1][0]),c=i(w[s][r][0],w[s][r+1][0]),x=i(w[s+1][r][0],w[s+1][r+1][0]),g=[[],[],[],[]];for(let t=0;t&lt;4;++t){(d=[])[0]=w[s][r][1][t],d[1]=w[s+1][r][1][t],d[2]=w[s][r+1][1][t],d[3]=w[s+1][r+1][1][t],d[4]=w[s][r][2][t]*n,d[5]=w[s+1][r][2][t]*n,d[6]=w[s][r+1][2][t]*o,d[7]=w[s+1][r+1][2][t]*o,d[8]=w[s][r][3][t]*c,d[9]=w[s+1][r][3][t]*x,d[10]=w[s][r+1][3][t]*c,d[11]=w[s+1][r+1][3][t]*x,d[12]=0,d[13]=0,d[14]=0,d[15]=0,u=f(d);for(let e=0;e&lt;9;++e){g[t][e]=[];for(let s=0;s&lt;9;++s)g[t][e][s]=p(u,e/8,s/8),g[t][e][s]&gt;255?g[t][e][s]=255:g[t][e][s]&lt;0&amp;&amp;(g[t][e][s]=0)}}h=[];for(let t=3*s,e=3*s+4;t&lt;e;++t)h.push(this.nodes[t].slice(3*r,3*r+4));l=y(h);for(let s=0;s&lt;8;++s)for(let r=0;r&lt;8;++r)(a=new m(l[s][r],[[[g[0][s][r],g[1][s][r],g[2][s][r],g[3][s][r]],[g[0][s][r+1],g[1][s][r+1],g[2][s][r+1],g[3][s][r+1]]],[[g[0][s+1][r],g[1][s+1][r],g[2][s+1][r],g[3][s+1][r]],[g[0][s+1][r+1],g[1][s+1][r+1],g[2][s+1][r+1],g[3][s+1][r+1]]]])).paint(t,e)}}}transform(t){if(t instanceof x)for(let e=0,s=this.nodes.length;e&lt;s;++e)for(let s=0,r=this.nodes[0].length;s&lt;r;++s)this.nodes[e][s]=this.nodes[e][s].add(t);else if(t instanceof g)for(let e=0,s=this.nodes.length;e&lt;s;++e)for(let s=0,r=this.nodes[0].length;s&lt;r;++s)this.nodes[e][s]=this.nodes[e][s].transform(t)}scale(t){for(let e=0,s=this.nodes.length;e&lt;s;++e)for(let s=0,r=this.nodes[0].length;s&lt;r;++s)this.nodes[e][s]=this.nodes[e][s].scale(t)}}document.querySelectorAll(&quot;rect,circle,ellipse,path,text&quot;).forEach((r,n)=&gt;{let o=r.getAttribute(&quot;id&quot;);o||(o=&quot;patchjs_shape&quot;+n,r.setAttribute(&quot;id&quot;,o));const i=r.style.fill.match(/^url\(\s*&quot;?\s*#([^\s&quot;]+)&quot;?\s*\)/),a=r.style.stroke.match(/^url\(\s*&quot;?\s*#([^\s&quot;]+)&quot;?\s*\)/);if(i&amp;&amp;i[1]){const a=document.getElementById(i[1]);if(a&amp;&amp;&quot;meshgradient&quot;===a.nodeName){const i=r.getBBox();let l=document.createElementNS(s,&quot;canvas&quot;);d(l,{width:i.width,height:i.height});const c=l.getContext(&quot;2d&quot;);let u=c.createImageData(i.width,i.height);const f=new b(a);&quot;objectBoundingBox&quot;===a.getAttribute(&quot;gradientUnits&quot;)&amp;&amp;f.scale(new x(i.width,i.height));const p=a.getAttribute(&quot;gradientTransform&quot;);null!=p&amp;&amp;f.transform(h(p)),&quot;userSpaceOnUse&quot;===a.getAttribute(&quot;gradientUnits&quot;)&amp;&amp;f.transform(new x(-i.x,-i.y)),f.paintMesh(u.data,l.width),c.putImageData(u,0,0);const y=document.createElementNS(t,&quot;image&quot;);d(y,{width:i.width,height:i.height,x:i.x,y:i.y});let g=l.toDataURL();y.setAttributeNS(e,&quot;xlink:href&quot;,g),r.parentNode.insertBefore(y,r),r.style.fill=&quot;none&quot;;const w=document.createElementNS(t,&quot;use&quot;);w.setAttributeNS(e,&quot;xlink:href&quot;,&quot;#&quot;+o);const m=&quot;patchjs_clip&quot;+n,M=document.createElementNS(t,&quot;clipPath&quot;);M.setAttribute(&quot;id&quot;,m),M.appendChild(w),r.parentElement.insertBefore(M,r),y.setAttribute(&quot;clip-path&quot;,&quot;url(#&quot;+m+&quot;)&quot;),u=null,l=null,g=null}}if(a&amp;&amp;a[1]){const o=document.getElementById(a[1]);if(o&amp;&amp;&quot;meshgradient&quot;===o.nodeName){const i=parseFloat(r.style.strokeWidth.slice(0,-2))*(parseFloat(r.style.strokeMiterlimit)||parseFloat(r.getAttribute(&quot;stroke-miterlimit&quot;))||1),a=r.getBBox(),l=Math.trunc(a.width+i),c=Math.trunc(a.height+i),u=Math.trunc(a.x-i/2),f=Math.trunc(a.y-i/2);let p=document.createElementNS(s,&quot;canvas&quot;);d(p,{width:l,height:c});const y=p.getContext(&quot;2d&quot;);let g=y.createImageData(l,c);const w=new b(o);&quot;objectBoundingBox&quot;===o.getAttribute(&quot;gradientUnits&quot;)&amp;&amp;w.scale(new x(l,c));const m=o.getAttribute(&quot;gradientTransform&quot;);null!=m&amp;&amp;w.transform(h(m)),&quot;userSpaceOnUse&quot;===o.getAttribute(&quot;gradientUnits&quot;)&amp;&amp;w.transform(new x(-u,-f)),w.paintMesh(g.data,p.width),y.putImageData(g,0,0);const M=document.createElementNS(t,&quot;image&quot;);d(M,{width:l,height:c,x:0,y:0});let S=p.toDataURL();M.setAttributeNS(e,&quot;xlink:href&quot;,S);const k=&quot;pattern_clip&quot;+n,A=document.createElementNS(t,&quot;pattern&quot;);d(A,{id:k,patternUnits:&quot;userSpaceOnUse&quot;,width:l,height:c,x:u,y:f}),A.appendChild(M),o.parentNode.appendChild(A),r.style.stroke=&quot;url(#&quot;+k+&quot;)&quot;,g=null,p=null,S=null}}})}();
                    </script>
                </svg>
            </a>

            <div class="d-flex">
                <!--
                    <div class="bd-search" id="docsearch" data-bd-docs-version="5.3"><button type="button"
                        class="DocSearch DocSearch-Button" aria-label="Search">
                            <span
                            class="DocSearch-Button-Container"><svg width="20" height="20" class="DocSearch-Search-Icon"
                                viewBox="0 0 20 20">
                                <path
                                    d="M14.386 14.386l4.0877 4.0877-4.0877-4.0877c-2.9418 2.9419-7.7115 2.9419-10.6533 0-2.9419-2.9418-2.9419-7.7115 0-10.6533 2.9418-2.9419 7.7115-2.9419 10.6533 0 2.9419 2.9418 2.9419 7.7115 0 10.6533z"
                                    stroke="currentColor" fill="none" fill-rule="evenodd" stroke-linecap="round"
                                    stroke-linejoin="round"></path>
                            </svg><span class="DocSearch-Button-Placeholder">Search</span></span><span
                            class="DocSearch-Button-Keys"><kbd class="DocSearch-Button-Key"><svg width="15" height="15"
                                    class="DocSearch-Control-Key-Icon">
                                    <path
                                        d="M4.505 4.496h2M5.505 5.496v5M8.216 4.496l.055 5.993M10 7.5c.333.333.5.667.5 1v2M12.326 4.5v5.996M8.384 4.496c1.674 0 2.116 0 2.116 1.5s-.442 1.5-2.116 1.5M3.205 9.303c-.09.448-.277 1.21-1.241 1.203C1 10.5.5 9.513.5 8V7c0-1.57.5-2.5 1.464-2.494.964.006 1.134.598 1.24 1.342M12.553 10.5h1.953"
                                        stroke-width="1.2" stroke="currentColor" fill="none" stroke-linecap="square">
                                    </path>
                                </svg></kbd><kbd class="DocSearch-Button-Key">K</kbd></span></button></div>
                            -->
                <button class="navbar-toggler d-flex d-lg-none order-3 p-2" type="button" data-bs-toggle="offcanvas"
                    data-bs-target="#bdNavbar" aria-controls="bdNavbar" aria-label="Toggle navigation">
                    <svg class="bi" aria-hidden="true">
                        <use xlink:href="#three-dots"></use>
                    </svg>
                </button>
            </div>

            <div class="offcanvas-lg offcanvas-end flex-grow-1" tabindex="-1" id="bdNavbar"
                aria-labelledby="bdNavbarOffcanvasLabel" data-bs-scroll="true">
                <div class="offcanvas-header px-4 pb-0">
                    <h5 class="offcanvas-title text-white" id="bdNavbarOffcanvasLabel">New Poste</h5>
                    <button type="button" class="btn-close btn-close-white" data-bs-dismiss="offcanvas"
                        aria-label="Close" data-bs-target="#bdNavbar"></button>
                </div>

                <div class="offcanvas-body p-4 pt-0 p-lg-0">
                    <hr class="d-lg-none text-white-50">
                    <ul class="navbar-nav flex-row flex-wrap bd-navbar-nav">
                        <li class="nav-item col-6 col-lg-auto">
                            <a class="nav-link py-2 px-0 px-lg-2 " aria-current="true"
                                href="https://www.new-poste.info/p/devlopement-tutorials-html-css.html"
                                onclick="ga('send', 'event', 'Navbar', 'Community links', 'Docs');">Learn HTML</a>
                        </li>
                        <li class="nav-item col-6 col-lg-auto">
                            <a class="nav-link py-2 px-0 px-lg-2"
                                href="https://www.new-poste.info/p/javascript-tutorials.html"
                                onclick="ga('send', 'event', 'Navbar', 'Community links', 'Examples');">Learn
                                JavaScript</a>
                        </li>
                        <li class="nav-item col-6 col-lg-auto">
                            <a class="nav-link py-2 px-0 px-lg-2" href="https://www.new-poste.info/p/learn-css.html"
                                onclick="ga('send', 'event', 'Navbar', 'Community links', 'Icons');"
                                rel="noopener">Learn CSS</a>
                        </li>
                        <li class="nav-item col-6 col-lg-auto">
                            <a class="nav-link py-2 px-0 px-lg-2"
                                href="https://www.new-poste.info/p/react-tutorials.html"
                                onclick="ga('send', 'event', 'Navbar', 'Community links', 'Themes');"
                                rel="noopener">Learn React</a>
                        </li>
                        <li class="nav-item col-6 col-lg-auto">
                            <a class="nav-link py-2 px-0 px-lg-2" href="https://www.new-poste.info/p/how-to-this.html"
                                onclick="ga('send', 'event', 'Navbar', 'Community links', 'Blog');" rel="noopener">How
                                To ?</a>
                        </li>
                      <li class="nav-item col-6 col-lg-auto">
                            <a class="nav-link py-2 px-0 px-lg-2" href="https://www.new-poste.info/p/registration-form.html"
                                onclick="ga('send', 'event', 'Navbar', 'Community links', 'Blog');" rel="noopener">Contact Us</a>
                        </li>
                    </ul>

                    <hr class="d-lg-none text-white-50">

                    <ul class="navbar-nav flex-row flex-wrap ms-md-auto">
                        <li class="nav-item col-6 col-lg-auto">
                            <a class="nav-link py-2 px-0 px-lg-2" href="https://github.com/New-poste" rel="noopener">
                                <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" class="navbar-nav-svg"
                                    viewBox="0 0 512 499.36" role="img">
                                    <title>GitHub</title>
                                    <path fill="currentColor" fill-rule="evenodd"
                                        d="M256 0C114.64 0 0 114.61 0 256c0 113.09 73.34 209 175.08 242.9 12.8 2.35 17.47-5.56 17.47-12.34 0-6.08-.22-22.18-.35-43.54-71.2 15.49-86.2-34.34-86.2-34.34-11.64-29.57-28.42-37.45-28.42-37.45-23.27-15.84 1.73-15.55 1.73-15.55 25.69 1.81 39.21 26.38 39.21 26.38 22.84 39.12 59.92 27.82 74.5 21.27 2.33-16.54 8.94-27.82 16.25-34.22-56.84-6.43-116.6-28.43-116.6-126.49 0-27.95 10-50.8 26.35-68.69-2.63-6.48-11.42-32.5 2.51-67.75 0 0 21.49-6.88 70.4 26.24a242.65 242.65 0 0 1 128.18 0c48.87-33.13 70.33-26.24 70.33-26.24 14 35.25 5.18 61.27 2.55 67.75 16.41 17.9 26.31 40.75 26.31 68.69 0 98.35-59.85 120-116.88 126.32 9.19 7.9 17.38 23.53 17.38 47.41 0 34.22-.31 61.83-.31 70.23 0 6.85 4.61 14.81 17.6 12.31C438.72 464.97 512 369.08 512 256.02 512 114.62 397.37 0 256 0z">
                                    </path>
                                </svg>
                                <small class="d-lg-none ms-2">GitHub</small>
                            </a>
                        </li>
                        <li class="nav-item col-6 col-lg-auto">
                            <a class="nav-link py-2 px-0 px-lg-2" href='https://twitter.com/new_poste' rel="noopener">
                                <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" class="navbar-nav-svg"
                                    viewBox="0 0 512 416.32" role="img">
                                    <title>Twitter</title>
                                    <path fill="currentColor"
                                        d="M160.83 416.32c193.2 0 298.92-160.22 298.92-298.92 0-4.51 0-9-.2-13.52A214 214 0 0 0 512 49.38a212.93 212.93 0 0 1-60.44 16.6 105.7 105.7 0 0 0 46.3-58.19 209 209 0 0 1-66.79 25.37 105.09 105.09 0 0 0-181.73 71.91 116.12 116.12 0 0 0 2.66 24c-87.28-4.3-164.73-46.3-216.56-109.82A105.48 105.48 0 0 0 68 159.6a106.27 106.27 0 0 1-47.53-13.11v1.43a105.28 105.28 0 0 0 84.21 103.06 105.67 105.67 0 0 1-47.33 1.84 105.06 105.06 0 0 0 98.14 72.94A210.72 210.72 0 0 1 25 370.84a202.17 202.17 0 0 1-25-1.43 298.85 298.85 0 0 0 160.83 46.92">
                                    </path>
                                </svg>
                                <small class="d-lg-none ms-2">Twitter</small>
                            </a>
                        </li>
                        <li class="nav-item col-6 col-lg-auto">
                            <a class="nav-link py-2 px-0 px-lg-2" href="https://www.new-poste.info/p/about-us.html"
                                rel="noopener">
                                <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor"
                                    fill-rule="evenodd" class="navbar-nav-svg" viewBox="0 0 40 41" role="img">
                                    <title>About Us</title>
                                    <path fill-opacity=".4"
                                        d="M32.8 21c0 2.4-.8 4.9-2 6.9l5.1 5.1c2.5-3.4 4.1-7.6 4.1-12 0-4.6-1.6-8.8-4-12.2L30.7 14c1.2 2 2 4.3 2 7z">
                                    </path>
                                    <path
                                        d="M20 33.7a12.8 12.8 0 0 1 0-25.6c2.6 0 5 .7 7 2.1L32 5a20 20 0 1 0 .1 31.9l-5-5.2a13 13 0 0 1-7 2z">
                                    </path>
                                </svg>
                                <small class="d-lg-none ms-2">About Us</small>
                            </a>
                        </li>
                        <li class="nav-item py-2 py-lg-1 col-12 col-lg-auto">
                            <div class="vr d-none d-lg-flex h-100 mx-lg-2 text-white"></div>
                            <hr class="d-lg-none my-2 text-white-50">
                        </li>



                        


                        

                       
                    </ul>
                </div>
            </div>
        </nav>
    </header>



    <div class="container-xxl bd-gutter mt-3 my-md-4 bd-layout">
        <aside class="bd-sidebar">
            <div class="offcanvas-lg offcanvas-start" tabindex="-1" id="bdSidebar"
                aria-labelledby="bdSidebarOffcanvasLabel">
                <div class="offcanvas-header border-bottom">
                    <h5 class="offcanvas-title" id="bdSidebarOffcanvasLabel">Browse docs</h5>
                    <button type="button" class="btn-close" data-bs-dismiss="offcanvas" aria-label="Close"
                        data-bs-target="#bdSidebar"></button>
                </div>

                <div class="offcanvas-body">
                    <nav class="bd-links w-100" id="bd-docs-nav" aria-label="Docs navigation">
                        <h4>Javascript</h4>
                        <ul class="list-unstyled ">
                            <li class="my-2">

                                <ul class="list-unstyled ps-3">


                                    <li class="bas">JS Tutorial</li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-home.html">JS HOME</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-introduction.html">JS
                                            Introduction</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-wher-to.html">JS Where To</a>
                                    </li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-output.html">JS Output</a>
                                    </li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-statement.html">JS
                                            Statements</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-syntax.html">JS Syntax</a>
                                    </li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-comment.html">JS Comments</a>
                                    </li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-variables.html">JS
                                            Variables</a></li>
                                    <li style="background-color: rgba(237, 5, 243, 0.29);"><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-let.html">JS Let</a></li>
                                    <li><a
                                            class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-cont.html">JS Const</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-operateur.html">JS
                                            Operators</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-arithmetic.html">JS
                                            Arithmetic</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-assignment.html">JS
                                            Assignment</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-data-types.html">JS Data
                                            Types</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-function.html">JS
                                            Functions</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-objects.html">JS Objects</a>
                                    </li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-event.html">JS Events</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-strings.html">JS Strings</a>
                                    </li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-strings-methods.html">JS
                                            String Methods</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-string-search.html">JS String
                                            Search</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-string-templates.html">JS
                                            String Templates</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-numbers.html">JS Numbers</a>
                                    </li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-bigint.html">JS BigInt</a>
                                    </li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-tutorial.html">JS Number
                                            Methods</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-number-properties.html">JS
                                            Number Properties</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-arrays.html">JS Arrays</a>
                                    </li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-array-methods.html">JS Array
                                            Methods</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-aray-sort.html">JS Array
                                            Sort</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-aray-iteration.html">JS Array
                                            Iteration</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-aray-const.html">JS Array
                                            Const</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-dats.html">JS Dates</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-date-formats.html">JS Date
                                            Formats</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-date-get-methods.html">JS Date
                                            Get Methods</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-tutorial.html">JS Date Set
                                            Methods</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-math.html">JS Math</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-random.html">JS Random</a>
                                    </li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-booleans.html">JS Booleans</a>
                                    </li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-comparisons.html">JS
                                            Comparisons</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-if-else.html">JS If Else</a>
                                    </li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-szitch.html">JS Switch</a>
                                    </li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-loop-for.html">JS Loop For</a>
                                    </li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-loop-for-in.html">JS Loop For
                                            In</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-loop-for-of.html">JS Loop For
                                            Of</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-loop-while.html">JS Loop
                                            While</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-break.html">JS Break</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-iterables.html">JS
                                            Iterables</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-sets.html">JS Sets</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-maps.html">JS Maps</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-typof.html">JS Typeof</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-type-convertion.html">JS Type
                                            Conversion</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-bitwise.html">JS Bitwise</a>
                                    </li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-regexp.html">JS RegExp</a>
                                    </li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-precedence.html">JS
                                            Precedence</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-errors.html">JS Errors</a>
                                    </li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-scope.html">JS Scope</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-hoisting.html">JS Hoisting</a>
                                    </li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-strict-mode.html">JS Strict
                                            Mode</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-this-keyword.html">JS this
                                            Keyword</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-arroz-function.html">JS Arrow
                                            Function</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-classes.html">JS Classes</a>
                                    </li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-modules.html">JS Modules</a>
                                    </li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-json.html">JS JSON</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-debugging.html">JS
                                            Debugging</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-style-guide.html">JS Style
                                            Guide</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-best-pratices.html">JS Best
                                            Practices</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-mistakes.html">JS Mistakes</a>
                                    </li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-performance.html">JS
                                            Performance</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-reserved-words.html">JS
                                            Reserved Words</a></li>
                                </ul>

                                <ul class="list-unstyled ps-3">

                                    <li class="bas">JS Versions</li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-virsions.html">JS Versions</a>
                                    </li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-2009.html">JS 2009 (ES5)</a>
                                    </li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-2015.html">JS 2015 (ES6)</a>
                                    </li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-2016.html">JS 2016</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-2017.html">JS 2017</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-2018.html">JS 2018</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-2019.html">JS 2019</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-2020.html">JS 2020</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-2021-2022.html">JS
                                            2021/2022</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-ie-edge.html">JS IE / Edge</a>
                                    </li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-history.html">JS History</a>
                                    </li>
                                </ul>
                                <ul class="list-unstyled ps-3">

                                    <li class="bas">JS Objects</li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-object-definitions.html">Object
                                            Definitions</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-object-properties.html">Object
                                            Properties</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-object-methods.html">Object
                                            Methods</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-object-display.html">Object
                                            Display</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-object-accessoirs.html">Object
                                            Accessors</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-object-constructors.html">Object
                                            Constructors</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-object-prototypes.html">
                                            Object Prototypes</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-object-iterables.html">Object
                                            Iterables</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-object-sets.html">Object
                                            Sets</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-object-maps.html"> Object
                                            Maps</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-object-reference.html"> Object
                                            Reference</a></li>
                                </ul>
                                <ul class="list-unstyled ps-3">

                                    <li class="bas"> JS Functions</li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-function-definitions.html">Function
                                            Definitions</a>
                                    </li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-function-parameters.html">
                                            Function Parameters</a>
                                    </li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-function-invocations.html">Function
                                            Invocation</a>
                                    </li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-function-call.html"> Function
                                            Call</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-function-apply.html"> Function
                                            Apply</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-function-bind.html"> Function
                                            Bind</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-function-closures.html">
                                            Function Closures</a></li>
                                </ul>
                                <ul class="list-unstyled ps-3">

                                    <li class="bas">JS Classes</li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-class-into.html">Class
                                            Intro</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-class-inheritance.html">Class
                                            Inheritance</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-class-static.html"> Class
                                            Static</a></li>
                                </ul>
                                <ul class="list-unstyled ps-3">

                                    <li class="bas">JS Async</li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-callbacks.html"> JS
                                            Callbacks</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-asynchronous.html"> JS
                                            Asynchronous</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-promises.html">JS Promises</a>
                                    </li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-async-await">JS
                                            Async/Await</a></li>
                                </ul>
                                <ul class="list-unstyled ps-3">

                                    <li class="bas"> JS HTML DOM</li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-dom-intro.html">DOM Intro</a>
                                    </li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-dom-methods.html"> DOM
                                            Methods</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-dom-document.html"> DOM
                                            Document</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-dom-element.html"> DOM
                                            Elements</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-dom-html.html">DOM HTML</a>
                                    </li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-domforms.html"> DOM Forms</a>
                                    </li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-dom-css.html"> DOM CSS</a>
                                    </li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-dom-animations.html"> DOM
                                            Animations</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-dom-events.html">DOM
                                            Events</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-dom-event-listener.html"> DOM
                                            Event Listener</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-dom-navigetion.html"> DOM
                                            Navigation</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-dom-nodes.html"> DOM Nodes</a>
                                    </li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-dom-collections.html"> DOM
                                            Collections</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-dom-node-listes.html"> DOM
                                            Node Lists</a></li>
                                </ul>
                                <ul class="list-unstyled ps-3">

                                    <li class="bas"> JS Browser BOM</li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-window.html"> JS Window</a>
                                    </li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-screen.html">JS Screen</a>
                                    </li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-location.html"> JS
                                            Location</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-history.html"> JS History</a>
                                    </li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-navigateur.html"> JS
                                            Navigator</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-popup-alert.html"> JS Popup
                                            Alert</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-timing.html"> JS Timing</a>
                                    </li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-cookies.html"> JS Cookies</a>
                                    </li>
                                </ul>
                                <ul class="list-unstyled ps-3">

                                    <li class="bas"> JS Web APIs</li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-web-api-intro.html"> Web API
                                            Intro</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-web-forms-api.html"> Web Forms
                                            API</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-web-history-api.html"> Web
                                            History API</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-web-storage-api.html"> Web
                                            Storage API</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-web-worker-api.html"> Web
                                            Worker API</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-web-fetch-api.html"> Web Fetch
                                            API</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-web-geolocation-api.html"> Web
                                            Geolocation API</a>
                                    </li>
                                </ul>
                                <ul class="list-unstyled ps-3">

                                    <li class="bas"> JS AJAX</li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-ajax-intro.html"> AJAX
                                            Intro</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-ajax-xmlhttp.html"> AJAX
                                            XMLHttp</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-ajax-request.html"> AJAX
                                            Request</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-ajax-response.html"> AJAX
                                            Response</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-ajax-xml-file.html"> AJAX XML
                                            File</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-ajax-php.html"> AJAX PHP</a>
                                    </li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-ajax-asp.html"> AJAX ASP</a>
                                    </li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-ajax-database.html"> AJAX
                                            Database</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-ajax-applications.html"> AJAX
                                            Applications</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-ajax-examples.html"> AJAX
                                            Examples</a></li>
                                </ul>
                                <ul class="list-unstyled ps-3">

                                    <li class="bas"> JS JSON</li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-json-intro.html">JSON
                                            Intro</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-json-syntax.html">JSON
                                            Syntax</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-json-vs-xml.html">JSON vs
                                            XML</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-json-data-types.html">JSON
                                            Data Types</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-json-parse.html">JSON
                                            Parse</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-json-stringify.html">JSON
                                            Stringify</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-json-objects.html">JSON
                                            Objects</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-json-arrys.html">JSON
                                            Arrays</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-json-server.html">JSON
                                            Server</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-json-php.html">JSON PHP</a>
                                    </li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-json-html.html">JSON HTML</a>
                                    </li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-json-jsonp.html">JSON
                                            JSONP</a></li>
                                </ul>
                                <ul class="list-unstyled ps-3">

                                    <li class="bas">JS vs jQuery</li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-jquery-selecteurs.html">jQuery
                                            Selectors</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-jquery-html.html">jQuery
                                            HTML</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-jquery-css.html">jQuery
                                            CSS</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-jquery-dom.html">jQuery
                                            DOM</a></li>
                                </ul>
                                <ul class="list-unstyled ps-3">

                                    <li class="bas">JS Graphics</li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-graphics.html">JS Graphics</a>
                                    </li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-canvas.html">JS Canvas</a>
                                    </li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-plotly.html">JS Plotly</a>
                                    </li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-chartjs.html">JS Chartjs</a>
                                    </li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-google-chart.html">JS Google
                                            Chart</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-d3-js.html">JS D3 js</a></li>
                                </ul>
                                <ul class="list-unstyled ps-3">

                                    <li class="bas">JS Examples</li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-examples.html">JS Examples</a>
                                    </li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-html-dom.html">JS HTML DOM</a>
                                    </li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-html-input.html">JS HTML
                                            Input</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-html-object.html">JS HTML
                                            Objects</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-html-event.html">JS HTML
                                            Events</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-browser.html">JS Browser</a>
                                    </li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-editeus.html">JS Editor</a>
                                    </li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-exercises.html">JS
                                            Exercises</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-quiz.html">JS Quiz</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-bootcamp.html"> JS
                                            Bootcamp</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-certificate.html">JS
                                            Certificate</a></li>
                                </ul>
                                <ul class="list-unstyled ps-3">

                                    <li class="bas">JS References</li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/javascript-opjects.html">JavaScript
                                            Objects</a></li>
                                    <li><a class="d-inline-flex align-items-center rounded text-decoration-none"
                                            href="https://www.new-poste.info/p/html-dom-opjects.html">HTML DOM
                                            Objects</a></li>
                                </ul>

                            </li>
                        </ul>
                    </nav>

                </div>
            </div>
        </aside>

        <main class="bd-main order-1">
            <div class="bd-intro pt-2 ps-lg-2">
                <div class="d-md-flex flex-md-row-reverse align-items-center justify-content-between">
                    <div class="mb-3 mb-md-0 d-flex text-nowrap"><a class="btn btn-sm btn-bd-light rounded-2" href="#"
                            title="View and edit this file on GitHub" rel="noopener">
                            View on GitHub
                        </a>
                    </div>
                    <h1 class="bd-title mb-0" id="content">Get started with New Poste</h1>
                </div>
                <p class="bd-lead">New Poste It is an educational platform based on simplifying the principles of
                    self-learning based on the development of programmers.</p>
                <!--<script async="" src="https://cdn.carbonads.com/carbon.js?serve=CKYIKKJL&amp;placement=getbootstrapcom"
                    id="_carbonads_js"></script>
                <div id="carbonads"><span><span class="carbon-wrap"><a
                                href="https://srv.carbonads.net/ads/click/x/GTND42J7CKBIPK3MFT74YKQNF67IE27UFTBI4Z3JCYAIVK3MCY7DC23KCABIE23NCVAI5K3ECKYI62J7CV7DV5QKC6SDLK7MFTYDVK3EHJNCLSIZ?segment=placement:getbootstrapcom;"
                                class="carbon-img"  rel="noopener sponsored"><img
                                    src="https://cdn4.buysellads.net/uu/1/134955/1685040254-deisgndotdev3.jpg"
                                    alt="ads via Carbon" border="0" height="100" width="130"
                                    style="max-width: 130px;"></a><a
                                href="https://srv.carbonads.net/ads/click/x/GTND42J7CKBIPK3MFT74YKQNF67IE27UFTBI4Z3JCYAIVK3MCY7DC23KCABIE23NCVAI5K3ECKYI62J7CV7DV5QKC6SDLK7MFTYDVK3EHJNCLSIZ?segment=placement:getbootstrapcom;"
                                class="carbon-text"  rel="noopener sponsored"></a></span><a
                            href="http://carbonads.net/?utm_source=getbootstrapcom&amp;utm_medium=ad_via_link&amp;utm_campaign=in_unit&amp;utm_term=carbon"
                            class="carbon-poweredby"  rel="noopener sponsored"></a></span>
                </div>-->

            </div>


            <div class="bd-toc mt-3 mb-5 my-lg-0 mb-lg-5 px-sm-1 text-body-secondary">
                <button class="btn btn-link p-md-0 mb-2 mb-md-0 text-decoration-none bd-toc-toggle d-md-none"
                    type="button" data-bs-toggle="collapse" data-bs-target="#tocContents" aria-expanded="false"
                    aria-controls="tocContents">
                    On this page
                    <svg class="bi d-md-none ms-2" aria-hidden="true">
                        <use xlink:href="#chevron-expand"></use>
                    </svg>
                </button>
                <strong class="d-none d-md-block h6 my-2 ms-3">On this page</strong>
                <hr class="d-none d-md-block my-2 ms-3">
                <div class="collapse bd-toc-collapse" id="tocContents">
                    <nav id="TableOfContents">
                        <ul>
                            <li><a href="#form" class="active">javascript let</a></li>
                            <li><a href="#form1" class="">block scope functions?</a></li>
                            <li><a href="#form2" class="">Redeclaring Variables</a></li>
                            <li><a href="#form3" class="">differences between var, let and const</a></li>
                            <li><a href="#form4" class="">Redeclaring</a>
                               
                                    
                                    
                               
                           
                            
                        </ul>
                    </nav>
                </div>
            </div>

            <!--start----------------------------------------------------------------------------------->
            <div class="bd-content ps-lg-2">
                <section id="content">
      
        <!--javascript let-->
       <article class="my-3" id="form">
            <div class="bd-heading sticky-xl-top align-self-start mt-5 mb-3 mt-xl-0 mb-xl-2">
                
               <h1 class="text-center">javascript let</h1>
            </div>


            <div class="row justify-content-center">

                <div class="modal-button">
                   <h2 class="text-center">how does let work in javascript</h2><br /><br />
                    <button class="btn btn-primary" type="button"><a class="nav-link" href="https://www.new-poste.info/p/javascript-variables.html"> ❮ Previous</a></button>
                   <button class="btn btn-primary" style="float: right;" type="button">
                    <a class="nav-link" href="https://www.new-poste.info/p/javascript-cont.html"> Next ❯</a></button><br /><br /><div class="lil">
                  <label>Here are the frequently asked questions about The <span class="sas">let</span> keyword</label>
                  <br /><ol>
                 <li>When were keywords introduced in The <span class="sas">let</span> keyword In javascript<ul>
                   <li>In javascript  The <span class="sas">let</span> keyword was introduced in <a  href="https://www.new-poste.info/p/javascript-2015.html">ES6 (2015)</a></li></ul></li>
                  
                <li>Can variables in The keyword <span class="sas">let</span> take another block?
                  <ul>
                   <li> All variables listed in The keyword <span class="sas">let</span> cannot be changed. </li></ul>
                  </li> 
                    
                    
                    
                    
                    
                    
                    
                  <li>What is the most important thing to focus on before starting to use The keyword <span class="sas">let</span> in Javascript<ul>
                   <li>Before proceeding with the use of The keyword <span class="sas">let</span> in Javascript all variables must be declared. </li></ul></li>
                    
                    
                    
                    
                    
                   <li>Can a variable The keyword <span class="sas">let</span> take forms in Javascript<ul>
                   <li>Variables already defined in The keyword <span class="sas">let</span> in Javascript cannot take another block.</li></ul></li>
                  </ol>
                  </div>
                 <p>In The keyword <span class="sas">let</span> you cannot re-declare a variable more than once<br>
                   This example shows how?</p>
                  
              
                  <div class="notis">Rejected case with The keyword <span class="sas">let</span> in Javascript</div>
                                    <div class="container-fixed source">
<pre><button class="copbut" onclick="copyToClipboard('a1')" title="click to copy"><i class="bx bx-copy-alt">Copy</i></button><code class="javascript sid"> 
let x = "Mourad";

let x = 7;

                            </code>
</pre>
                  </div>  
                  <span id="a1"><!--
let x = "Mourad";

let x = 7;
--></span><br />
                  <p class="note">But in case <span class="sas">var</span> in Javascript it is possible</p> 
           <br />
              
                                                <div class="container-fixed source">
<pre><button class="copbut" onclick="copyToClipboard('a2')" title="click to copy"><i class="bx bx-copy-alt">Copy</i></button><code class="javascript sid"> 
var x = "Mourad";

var x = 7;
                            </code>
</pre>
                  </div>        
                  <span id="a2"><!--
var x = "Mourad";

var x = 7;--></span>      
                  
      
                  
 <hr />
                </div>
            </div>
        </article>
       
       <!--block scope functions?-->
       <article class="my-3" id="form1">
          



            <div class="row justify-content-center">

                <div class="modal-button">
                    <h2>block scope functions?</h2><br /><br />
                  <p>Before ES6 (2015), JavaScript had Global Scope and Function Scope.<br>
                  ES6 introduced two important new JavaScript keywords: <span class="sas">let</span> and <span class="sas">const</span>.<br>

These two keywords provide Block Scope in JavaScript.<br>

Variables declared inside a <span class="sas">{ }</span> block cannot be accessed from outside the block:<br>
                  </p>
                  
                   <div class="container-fixed source">
<pre><button class="copbut" onclick="copyToClipboard('a3')" title="click to copy"><i class="bx bx-copy-alt">Copy</i></button><code class="javascript sid"> 
{
let x = 7;
}


//In this case, it cannot be used x here
                            </code>
</pre>
                  </div>  
                  <span id="a3"><!--
{
let x = 7;
}
//In this case, it cannot be used x here
--></span><br /><p class="note">Variables declared with the  <span class="sas">var</span>  keyword can NOT have block scope.

Variables declared inside a  <span class="sas">{ }</span>  block can be accessed from outside the block.</p><br />
                                     <div class="container-fixed source">
<pre><button class="copbut" onclick="copyToClipboard('a4')" title="click to copy"><i class="bx bx-copy-alt">Copy</i></button><code class="javascript sid"> 
{
var x = 7;
}

// x CAN be used here

                            </code>
</pre>
                  </div>            
                  <span id="a4"><!--
{
var x = 7;
}

// x CAN be used here

--></span>
                  <div class="note"><ul><legend>Note</legend>
                  <li>A block scope in JavaScript is a scope that defines the availability of variables within the code. </li>
            <li>It can be declared using curly braces <span class="sas">{}</span>.</li>
                    <li>Scopes can be created within scopes. Variables within scopes can be declared using <span class="sas">let</span> or const.</li>
                   <li> Variables created in parent scope can be used in child scopes. </li>
                    <li>Variables created in sub scopes cannot be used in the parent scope.</li>
                  </ul>
                  </div>  
             
                  <hr />
              </div>
         </div>
         </article>
      <!--Redeclaring Variables-->
       <article class="my-3" id="form2">
           


            <div class="row justify-content-center">

                <div class="modal-button">
                    <h2>Redeclaring Variables</h2><br /><br />
                   
                  <p>Redeclaring a variable is useful in situations where it cannot be known if the variable has already been defined. By redeclaring a variable conditionally,</p>
<ol>
  <li>Redeclaring a variable means to declare an already declared variable or identifier again. </li>
  <li>Depending on the programming language and the scope of the variable, redeclaring a variable can have different effects. </li>
<li> in JavaScript, redeclaring a variable with <span class="sas">var</span> can overwrite the previous value, </li>
  </ol>

 <br />
                 
                    <div class="container-fixed source">
<pre><button class="copbut" onclick="copyToClipboard('a7')" title="click to copy"><i class="bx bx-copy-alt">Copy</i></button><code class="javaScript sid"> 

var x = 20
// Here x is 20

{
var x = 4;
// Here x is 4
}

// Here x is 4
                            </code>
</pre>
                  </div>   <button class="btn btn-primary" type="button"><a class="nav-link" href="https://poste.new-poste.info/p/redeclaring-variable-using-var.html" target="_blank">Get Coding&gt;&gt;&gt;</a>
</button>            
                  <span id="a7"><!--
var x = 20
// Here x is 20

{
var x = 4;
// Here x is 4
}

// Here x is 4
--></span>
                  
            <p>while redeclaring a variable with <span class="sas">let</span> can create a new variable in a different block.</p>
                  
                  
                  
                  
                  
                                     <div class="container-fixed source">
<pre><button class="copbut" onclick="copyToClipboard('a8')" title="click to copy"><i class="bx bx-copy-alt">Copy</i></button><code class="javaScript sid"> 

let = 20
// Here x is 20

{
let = 4;
// Here x is 4
}

// Here x is 4
                            </code>
</pre>
                  </div>   <button class="btn btn-primary" type="button"><a class="nav-link" href="https://poste.new-poste.info/p/redeclaring-variable-using-let.html" target="_blank">Get Coding&gt;&gt;&gt;</a>
</button>            
                  <span id="a8"><!--
let = 20
// Here x is 20

{
let = 4;
// Here x is 4
}

// Here x is 4
--></span>
                  <br />
                  
                  
                 <hr />
                <p></p><p></p></div>
            </div>
    </article>
        
      <!--differences between var, let and const-->
        <article class="my-3" id="form3">
           


            <div class="row justify-content-center">

                <div class="modal-button">
                      <h2>the differences between var, let and const</h2>
                 <ol>
<span class="sas">var</span>, <span class="sas">let</span>, and <span class="sas">const</span> are keywords to declare variables in JavaScript. They have different scopes and behaviors.

<li><span class="sas">var</span> variables are globally or function scoped, and can be updated and re-declared within their scope.</li>
<li><span class="sas">let</span> variables are block scoped, and can be updated but not re-declared within their scope.</li>
<li><span class="sas">const</span> variables are also block scoped, but they cannot be updated or re-declared within their scope.</li>
                  <li><span class="sas">const</span> creates constants that cannot be changed or redeclared, while let and var create variables that can be reassigned </li>
                  
                  
                  </ol><div class="note">
It is recommended to use <span class="sas">let</span> or <span class="sas">const</span> instead of <span class="sas">var</span>, as they provide more clarity and prevent errors.</div>

                               
             
                  <br />
                  <h3>This Table For the differences between var, let and const</h3>
                  <table class="table table-sm table-bordered">
    <tbody >
        <tr ></tr>
        <tr >
            <td ></td>
            <td scope="col">Scope</td>
            <td scope="col">Redeclare</td>
            <td scope="col">Reassign</td>
            <td scope="col">Hoisted</td>
            <td scope="col">Binds this</td>
        </tr>
        <tr >
            <td >var</td>
            <td >No</td>
            <td >Yes</td>
            <td >Yes</td>
            <td >Yes</td>
            <td >Yes</td>
        </tr>
        <tr >
            <td >let</td>
            <td >Yes</td>
            <td >No</td>
            <td >Yes</td>
            <td >No</td>
            <td >No</td>
        </tr>
        <tr >
            <td >const</td>
            <td >Yes</td>
            <td >No</td>
            <td >No</td>
            <td >No</td>
            <td >No</td>
        </tr>
    </tbody>
</table>
                  <h2>The Best Of <span class="sas">const</span> and <span class="sas">let</span></h2>       
                <ul>
                  <li><span class="sas">const</span> and <span class="sas">let</span>  from keywords in Javascript have a block range </li>
                   <li>  As for redefining variables, the <span class="sas">const</span> and <span class="sas">let</span> cannot</li>
                  <li>  When it comes to <span class="sas">const</span> and <span class="sas">let</span> the programmer has to set them both before starting to edit the code.</li>
                  
                  <li> Actually, variables defined with <span class="sas">let</span> and <span class="sas">const</span> are hoisted to the top of the block, but not initialized. Meaning: The block of code is aware of the variable, but it cannot be used until it has been declared. Using a let or const variable before it is declared will result in a ReferenceError</li>
                  </ul> 
                  <p class="note"><span class="sad">Note</span>
let and <span class="sas">const</span> variables are hoisted, but they are not initialized with a default value like <span class="sas">var</span> variables. <br>This means they cannot be accessed before their declaration, unlike var variables which are initialized with undefined. <br>Also, <span class="sas">let</span> and <span class="sas">const</span> variables are block scoped, meaning they only exist within the block where they are declared <span class="sas">var</span> variables are either global scoped or function scoped.<br> Therefore, <span class="sas">let</span> and <span class="sas">const</span> variables do not bind to the global object this, while var variables do
                  
                  </p>
                  <h2>for more information </h2>
                  <p class="sid notis">
                     The <span class="sas">var</span> keyword is used to declare variables that are function scoped or global scoped. <br>
This means that the variables declared with var can be accessed within the function where they are defined, or anywhere in the code if they are not inside a function. 
The <span class="sas">var</span> keyword also allows hoisting, which means that the variables can be used before they are declared. <br>
 However, this can lead to some confusion and errors, so it is recommended to declare the variables at the top of the scope.  <br>
The <span class="sas">var</span> keyword also binds the variables to the this object, which refers to the current context of the code. 

                  </p>
                  <h2>Browser Support</h2>
                  <p><span class="sas">let</span> and <span class="sas">const</span> are not supported in Internet Explorer 11 or earlier, but they are supported by all modern browsers</p>
                 <hr />
                </div>
            </div>
        </article>
         <!--Redeclaring-->
        <article class="my-3" id="form4">
           

            <div class="row justify-content-center">

                <div class="modal-button">
                      <h2>Redeclaring Variables</h2>
                  <p>Redeclaring a variable means declaring it again with the same name. In JavaScript, you can redeclare a variable using the <span class="sas">var</span> keyword, but this can cause some problems. For example:</p>

                                
             
                  
                  <div class="container-fixed source">
<pre><button class="copbut" onclick="copyToClipboard('v1')" title="click to copy"><i class="bx bx-copy-alt">Copy</i></button><code class="javascript sid"> 
var x = 10; // global variable
console.log(x); // 10
function foo() {
  var x = 20; // local variable
  console.log(x); // 20
}
foo();
console.log(x); // 10


                            </code>
</pre>
                  </div>   <button class="btn btn-primary" type="button"><a class="nav-link" href="https://poste.new-poste.info/p/redeclaring.html" target="_blank">Get Coding&gt;&gt;&gt;</a>
</button>            
                  <span id="v1"><!--
var x = 10; // global variable
console.log(x); // 10
function foo() {
  var x = 20; // local variable
  console.log(x); // 20
}
foo();
console.log(x); // 10

--></span>
                  <br />
                  <p>In this code, there are two variables named <span class="sas">x</span>, one in the global scope and one in the function scope. They have different values and do not affect each other.

However, if you redeclare a variable with <span class="sas">var</span> in a different scope or block, it can change the value of the outer variable too. <br>For example:</p>
                                  <div class="container-fixed source">
<pre><button class="copbut" onclick="copyToClipboard('v2')" title="click to copy"><i class="bx bx-copy-alt">Copy</i></button><code class="javascript sid"> 
var x = 10; // global variable
console.log(x); // 10
if (true) {
  var x = 20; // redeclared variable
  console.log(x); // 20
}
console.log(x); // 20



                            </code>
</pre>
                  </div>   <button class="btn btn-primary" type="button"><a class="nav-link" href="https://poste.new-poste.info/p/redeclare-variable.html" target="_blank">Get Coding&gt;&gt;&gt;</a>
</button>            
                  <span id="v2"><!--
var x = 10; // global variable
console.log(x); // 10
if (true) {
  var x = 20; // redeclared variable
  console.log(x); // 20
}
console.log(x); // 20


--></span>
              <br>
                  <p>In this code, there is only one variable named x, which is in the global scope. The var keyword inside the if block does not create a new variable, but reassigns the existing one. This can lead to unexpected results and bugs.<br>

To avoid this problem, you can use the let or const keywords instead of var, which create block-scoped variables that do not affect the outer scope. For example:</p>
                  
                                                    <div class="container-fixed source">
<pre><button class="copbut" onclick="copyToClipboard('v3')" title="click to copy"><i class="bx bx-copy-alt">Copy</i></button><code class="javascript sid"> 
let x = 10; // global variable
console.log(x); // 10
if (true) {
  let x = 20; // block-scoped variable
  console.log(x); // 20
}
console.log(x); // 10




                            </code>
</pre>
                  </div>   <button class="btn btn-primary" type="button"><a class="nav-link" href="https://poste.new-poste.info/p/one-variable-named-x.html" target="_blank">Get Coding&gt;&gt;&gt;</a>
</button>            
                  <span id="v3"><!--
let x = 10; // global variable
console.log(x); // 10
if (true) {
  let x = 20; // block-scoped variable
  console.log(x); // 20
}
console.log(x); // 10



--></span>
                   <h2 class="text-center">how does let work in javascript</h2><br /><br />
                    <button class="btn btn-primary" type="button"><a class="nav-link" href="https://www.new-poste.info/p/javascript-variables.html"> ❮ Previous</a></button>
                   <button class="btn btn-primary" style="float: right;" type="button">
                    <a class="nav-link" href="https://www.new-poste.info/p/javascript-cont.html"> Next ❯</a></button>
                  <hr />
                </div>
            </div>
        </article>
      
  <!------------------------------------------------------------------------------------------>    
      
      
      
      
      
      
      
      
      
      
      
      
      
      
   
  </section>
              
            </div>
 <!--End----------------------------------------------------------------------------------->
        </main>
    </div>


    <footer class="bd-footer py-4 py-md-5 mt-5 bg-body-tertiary">
        <div class="container py-4 py-md-5 px-4 px-md-3 text-body-secondary">
            <div class="row">
                <div class="col-lg-3 mb-3">
                    <a class="d-inline-flex align-items-center mb-2 text-body-emphasis text-decoration-none" href="/"
                        aria-label="Bootstrap">
                        <svg height='43' id='svg1' inkscape:version='1.3-beta (cedbd6c6ff, 2023-05-28)'
                            sodipodi:docname='logo1.svg' version='1.1' viewBox='0 0 100 43' width='100'
                            xml:space='preserve' xmlns='http://www.w3.org/2000/svg'
                            xmlns:inkscape='http://www.inkscape.org/namespaces/inkscape'
                            xmlns:sodipodi='http://sodipodi.sourceforge.net/DTD/sodipodi-0.dtd'
                            xmlns:svg='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink'>
                            <defs id='defs1'>
                                <linearGradient id='swatch60' inkscape:swatch='solid'>
                                    <stop id='stop61' offset='0' style='stop-color:#000000;stop-opacity:1;' />
                                </linearGradient>
                                <linearGradient id='swatch47' inkscape:swatch='solid'>
                                    <stop id='stop47' offset='0' style='stop-color:#000000;stop-opacity:1;' />
                                </linearGradient><color-profile id='color-profile1' name='sRGB-IEC61966-2.1'
                                    xlink:href='../../../../Windows/system32/spool/drivers/color/sRGB%20Color%20Space%20Profile.icm' /><color-profile
                                    id='color-profile2' name='Agfa-:-Swop-Standard'
                                    xlink:href='../../../../Windows/system32/spool/drivers/color/RSWOP.icm' />
                                <rect height='16.124025' id='rect46' width='132.94417' x='-46.79129' y='9.4847212' />
                                <rect height='16.282104' id='rect45' width='80.778206' x='-45.052425' y='12.646295' />
                                <inkscape:path-effect apply_no_weight='true' apply_with_weight='true' effect='bspline'
                                    helper_size='0' id='path-effect21' is_visible='true' lpeversion='1.3'
                                    only_selected='false' steps='2' uniform='false'
                                    weight='33.333333' /><inkscape:path-effect apply_no_weight='true'
                                    apply_with_weight='true' effect='bspline' helper_size='0' id='path-effect19'
                                    is_visible='true' lpeversion='1.3' only_selected='false' steps='2' uniform='false'
                                    weight='33.333333' /><inkscape:path-effect apply_no_weight='true'
                                    apply_with_weight='true' effect='bspline' helper_size='0' id='path-effect17'
                                    is_visible='true' lpeversion='1.3' only_selected='false' steps='2' uniform='false'
                                    weight='33.333333' /><inkscape:path-effect apply_no_weight='true'
                                    apply_with_weight='true' effect='bspline' helper_size='0' id='path-effect16'
                                    is_visible='true' lpeversion='1.3' only_selected='false' steps='2' uniform='false'
                                    weight='33.333333' />
                                <filter height='1.1661645' id='filter21' inkscape:collect='always'
                                    style='color-interpolation-filters:sRGB' width='1.0322228' x='-0.026520189'
                                    y='-0.080939876'>
                                    <feGaussianBlur id='feGaussianBlur21' inkscape:collect='always'
                                        stdDeviation='0.001 0.124' />
                                </filter>
                                <meshgradient gradientUnits='userSpaceOnUse' id='meshgradient63'
                                    inkscape:collect='always' x='-45.728516' y='4.7821774'>
                                    <meshrow id='meshrow63'>
                                        <meshpatch id='meshpatch63'>
                                            <stop id='stop63' path='c 27.3385,0  54.6771,0  82.0156,0'
                                                style='stop-color:#ffffff;stop-opacity:1' />
                                            <stop id='stop64' path='c 0,4.29167  0,8.58333  0,12.875'
                                                style='stop-color:#808080;stop-opacity:1' />
                                            <stop id='stop65' path='c -27.3385,0  -54.6771,0  -82.0156,0'
                                                style='stop-color:#ffffff;stop-opacity:1' />
                                            <stop id='stop66' path='c 0,-4.29167  0,-8.58333  0,-12.875'
                                                style='stop-color:#808080;stop-opacity:1' />
                                        </meshpatch>
                                    </meshrow>
                                </meshgradient>
                                <meshgradient gradientUnits='userSpaceOnUse' id='meshgradient66'
                                    inkscape:collect='always' x='-45.173573' y='16.858828'>
                                    <meshrow id='meshrow66'>
                                        <meshpatch id='meshpatch66'>
                                            <stop id='stop67' path='c 14.624,0  29.248,0  43.872,0'
                                                style='stop-color:#ffffff;stop-opacity:1' />
                                            <stop id='stop68' path='c 0,3.83095  0,7.6619  0,11.4929'
                                                style='stop-color:#808080;stop-opacity:1' />
                                            <stop id='stop69' path='c -14.624,0  -29.248,0  -43.872,0'
                                                style='stop-color:#ffffff;stop-opacity:1' />
                                            <stop id='stop70' path='c 0,-3.83095  0,-7.6619  0,-11.4929'
                                                style='stop-color:#808080;stop-opacity:1' />
                                        </meshpatch>
                                    </meshrow>
                                </meshgradient>
                                <meshgradient gradientUnits='userSpaceOnUse' id='meshgradient70'
                                    inkscape:collect='always' x='-47.388943' y='-3.389169'>
                                    <meshrow id='meshrow70'>
                                        <meshpatch id='meshpatch70'>
                                            <stop id='stop71' path='c 23.5506,0  47.1012,0  70.6518,0'
                                                style='stop-color:#ffffff;stop-opacity:1' />
                                            <stop id='stop72' path='c 0,22.9307  0,45.8615  0,68.7922'
                                                style='stop-color:#808080;stop-opacity:1' />
                                            <stop id='stop73' path='c -23.5506,0  -47.1012,0  -70.6518,0'
                                                style='stop-color:#ffffff;stop-opacity:1' />
                                            <stop id='stop74' path='c 0,-22.9307  0,-45.8615  0,-68.7922'
                                                style='stop-color:#808080;stop-opacity:1' />
                                        </meshpatch>
                                    </meshrow>
                                </meshgradient>
                            </defs>
                            <sodipodi:namedview bordercolor='#000000' borderlayer='false' borderopacity='0.25'
                                guidecolor='#001be5' guidehicolor='#8b8b8b' guidehiopacity='0.49803922'
                                guideopacity='0.6' id='namedview1' inkscape:current-layer='g1' inkscape:cx='44.182992'
                                inkscape:cy='29.95591' inkscape:deskcolor='#d1d1d1' inkscape:lockguides='true'
                                inkscape:pagecheckerboard='true' inkscape:pageopacity='0.0'
                                inkscape:showpageshadow='false' inkscape:window-height='705'
                                inkscape:window-maximized='1' inkscape:window-width='1366' inkscape:window-x='-8'
                                inkscape:window-y='-8' inkscape:zoom='6.3259637' pagecolor='#000000'
                                shape-rendering='crispEdges' showborder='true' showgrid='false' />
                            <g id='g1' inkscape:groupmode='layer' inkscape:label='Image'>
                                <path
                                    d='m 22.872524,59.515776 c -62.20965,-42.93512 -62.20965,-42.93512 0,0 z M -40.90482,1.38687 c -0.10873,-0.0036 -0.219446,-1.14e-4 -0.328125,0.0098 -0.869432,0.07904 -1.711303,0.60538 -2.185547,1.738281 -0.474244,1.132901 -0.579994,2.871657 -0.474609,4.847656 0.105384,1.975999 0.4205,4.190386 1.158203,6.640625 0.737703,2.450239 1.897511,5.136234 3.214844,7.033204 1.317332,1.896969 2.79366,3.004102 3.689453,4.505859 0.895793,1.501757 1.210478,3.398127 -0.607422,4.267578 -1.8179,0.869451 -5.768037,0.710814 -7.638672,1.791016 -1.870635,1.080202 -1.660616,3.400325 0.236328,4.585937 1.896945,1.185612 5.480017,1.236826 7.429688,1.869141 1.949671,0.632315 2.264916,1.845773 1.369141,3.189453 -0.895775,1.34368 -3.003469,2.818759 -4.953126,4.583984 -1.949656,1.765225 -3.740964,3.819377 -4.689453,6.375 -0.948489,2.555624 -1.05344,5.611297 -0.710937,6.84961 0.342502,1.238312 1.133469,0.660328 1.976562,-0.367188 0.843094,-1.027516 1.739186,-2.504223 2.898438,-4.164062 1.159251,-1.65984 2.58131,-3.503056 4.16211,-4.925782 1.580799,-1.422725 3.319172,-2.424067 4.373046,-2.740234 1.053875,-0.316167 1.423575,0.05273 2.345704,1.291016 0.922128,1.238285 2.396011,3.34618 4.292968,5.216796 1.896957,1.870617 4.216025,3.502685 5.744141,4.451172 1.528115,0.948488 2.266947,1.212057 2.714844,1.396485 0.447896,0.184427 0.605509,0.289852 0.658203,-3.66211 0.05269,-3.951961 1.67e-4,-11.960647 0.210937,-16.65039 0.210771,-4.689743 0.68496,-6.059245 1.185547,-6.902344 0.500587,-0.843099 1.027588,-1.159945 1.34375,-2.134766 0.316162,-0.97482 0.421666,-2.608111 0.158203,-3.503906 -0.263463,-0.895828 -0.897267,-1.052933 -1.898437,-1.263706 -1.001171,-0.210773 -2.370332,-0.475811 -3.898438,-0.765625 -1.528106,-0.289813 -3.214286,-0.605964 -5.005859,-1.238281 C -33.448454,20.367511 -35.629868,15.744624 -36.752476,10.98648 -37.253064,8.747012 -37.675552,6.427702 -37.965367,4.925933 -38.255182,3.424164 -38.413046,2.739978 -38.939976,2.213042 -39.40104,1.751974 -40.143707,1.411724 -40.90482,1.38687 Z'
                                    id='path1' sodipodi:nodetypes='sssssssssssssssssssssssssssssssssssss'
                                    style='opacity:0.98;fill:#808080;stroke:url(#meshgradient70);stroke-opacity:1;filter:url(#filter21)'
                                    transform='matrix(0,0.46783465,-1.5238425,0,100.43732,22.667014)' />
                                <path
                                    d='m -38.414413,27.30165 c 8.085335,-0.909246 7.186778,-5.774026 13.170208,-0.249311 0.974851,0.560677 2.882536,0.622939 3.770716,0.07004 3.768486,-4.838915 12.9884469,-0.239885 19.929556,-0.05462 C -25.55495,13.931775 -33.28537,14.980765 -44.046399,27.511766 Z'
                                    id='path1-7'
                                    style='opacity:0.98;fill:#808080;stroke:url(#meshgradient66);stroke-opacity:1;filter:url(#filter21)'
                                    transform='matrix(2.2433868,0,0,1.3929431,102.21625,3.1531377)' /><text id='text45'
                                    style='font-size:16px;line-height:5.66666px;white-space:pre;shape-inside:url(#rect46);opacity:1;fill:#808080;fill-opacity:0.982979;stroke:url(#meshgradient63);stroke-opacity:1'
                                    transform='matrix(1.1039273,0,0,1.7147874,57.075712,3.1695034)'
                                    xml:space='preserve'>
                                    <tspan id='tspan2' x='-46.791016' y='16.91499'>New Poste </tspan>
                                </text>
                            </g>
                            <script id='mesh_polyfill' type='text/javascript'>
                            !function () {
                                const t =& quot; http://www.w3.org/2000/svg&quot;,e=&quot;http://www.w3.org/1999/xlink&quot;,s=&quot;http://www.w3.org/1999/xhtml&quot;,r=2;if(document.createElementNS(t,&quot;meshgradient&quot;).x)return;const n=(t,e,s,r)=&gt;{let n=new x(.5*(e.x+s.x),.5*(e.y+s.y)),o=new x(.5*(t.x+e.x),.5*(t.y+e.y)),i=new x(.5*(s.x+r.x),.5*(s.y+r.y)),a=new x(.5*(n.x+o.x),.5*(n.y+o.y)),h=new x(.5*(n.x+i.x),.5*(n.y+i.y)),l=new x(.5*(a.x+h.x),.5*(a.y+h.y));return[[t,o,a,l],[l,h,i,r]]},o=t=&gt;{let e=t[0].distSquared(t[1]),s=t[2].distSquared(t[3]),r=.25*t[0].distSquared(t[2]),n=.25*t[1].distSquared(t[3]),o=e&gt;s?e:s,i=r&gt;n?r:n;return 18*(o&gt;i?o:i)},i=(t,e)=&gt;Math.sqrt(t.distSquared(e)),a=(t,e)=&gt;t.scale(2/3).add(e.scale(1/3)),h=t=&gt;{let e,s,r,n,o,i,a,h=new g;return t.match(/(\w+\(\s*[^)]+\))+/g).forEach(t=&gt;{let l=t.match(/[\w.-]+/g),d=l.shift();switch(d){case&quot;translate&quot;:2===l.length?e=new g(1,0,0,1,l[0],l[1]):(console.error(&quot;mesh.js: translate does not have 2 arguments!&quot;),e=new g(1,0,0,1,0,0)),h=h.append(e);break;case&quot;scale&quot;:1===l.length?s=new g(l[0],0,0,l[0],0,0):2===l.length?s=new g(l[0],0,0,l[1],0,0):(console.error(&quot;mesh.js: scale does not have 1 or 2 arguments!&quot;),s=new g(1,0,0,1,0,0)),h=h.append(s);break;case&quot;rotate&quot;:if(3===l.length&amp;&amp;(e=new g(1,0,0,1,l[1],l[2]),h=h.append(e)),l[0]){r=l[0]*Math.PI/180;let t=Math.cos(r),e=Math.sin(r);Math.abs(t)&lt;1e-16&amp;&amp;(t=0),Math.abs(e)&lt;1e-16&amp;&amp;(e=0),a=new g(t,e,-e,t,0,0),h=h.append(a)}else console.error(&quot;math.js: No argument to rotate transform!&quot;);3===l.length&amp;&amp;(e=new g(1,0,0,1,-l[1],-l[2]),h=h.append(e));break;case&quot;skewX&quot;:l[0]?(r=l[0]*Math.PI/180,n=Math.tan(r),o=new g(1,0,n,1,0,0),h=h.append(o)):console.error(&quot;math.js: No argument to skewX transform!&quot;);break;case&quot;skewY&quot;:l[0]?(r=l[0]*Math.PI/180,n=Math.tan(r),i=new g(1,n,0,1,0,0),h=h.append(i)):console.error(&quot;math.js: No argument to skewY transform!&quot;);break;case&quot;matrix&quot;:6===l.length?h=h.append(new g(...l)):console.error(&quot;math.js: Incorrect number of arguments for matrix!&quot;);break;default:console.error(&quot;mesh.js: Unhandled transform type: &quot;+d)}}),h},l=t=&gt;{let e=[],s=t.split(/[ ,]+/);for(let t=0,r=s.length-1;t&lt;r;t+=2)e.push(new x(parseFloat(s[t]),parseFloat(s[t+1])));return e},d=(t,e)=&gt;{for(let s in e)t.setAttribute(s,e[s])},c=(t,e,s,r,n)=&gt;{let o,i,a=[0,0,0,0];for(let h=0;h&lt;3;++h)e[h]&lt;t[h]&amp;&amp;e[h]&lt;s[h]||t[h]&lt;e[h]&amp;&amp;s[h]&lt;e[h]?a[h]=0:(a[h]=.5*((e[h]-t[h])/r+(s[h]-e[h])/n),o=Math.abs(3*(e[h]-t[h])/r),i=Math.abs(3*(s[h]-e[h])/n),a[h]&gt;o?a[h]=o:a[h]&gt;i&amp;&amp;(a[h]=i));return a},u=[[1,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0],[0,0,0,0,1,0,0,0,0,0,0,0,0,0,0,0],[-3,3,0,0,-2,-1,0,0,0,0,0,0,0,0,0,0],[2,-2,0,0,1,1,0,0,0,0,0,0,0,0,0,0],[0,0,0,0,0,0,0,0,1,0,0,0,0,0,0,0],[0,0,0,0,0,0,0,0,0,0,0,0,1,0,0,0],[0,0,0,0,0,0,0,0,-3,3,0,0,-2,-1,0,0],[0,0,0,0,0,0,0,0,2,-2,0,0,1,1,0,0],[-3,0,3,0,0,0,0,0,-2,0,-1,0,0,0,0,0],[0,0,0,0,-3,0,3,0,0,0,0,0,-2,0,-1,0],[9,-9,-9,9,6,3,-6,-3,6,-6,3,-3,4,2,2,1],[-6,6,6,-6,-3,-3,3,3,-4,4,-2,2,-2,-2,-1,-1],[2,0,-2,0,0,0,0,0,1,0,1,0,0,0,0,0],[0,0,0,0,2,0,-2,0,0,0,0,0,1,0,1,0],[-6,6,6,-6,-4,-2,4,2,-3,3,-3,3,-2,-1,-2,-1],[4,-4,-4,4,2,2,-2,-2,2,-2,2,-2,1,1,1,1]],f=t=&gt;{let e=[];for(let s=0;s&lt;16;++s){e[s]=0;for(let r=0;r&lt;16;++r)e[s]+=u[s][r]*t[r]}return e},p=(t,e,s)=&gt;{const r=e*e,n=s*s,o=e*e*e,i=s*s*s;return t[0]+t[1]*e+t[2]*r+t[3]*o+t[4]*s+t[5]*s*e+t[6]*s*r+t[7]*s*o+t[8]*n+t[9]*n*e+t[10]*n*r+t[11]*n*o+t[12]*i+t[13]*i*e+t[14]*i*r+t[15]*i*o},y=t=&gt;{let e=[],s=[],r=[];for(let s=0;s&lt;4;++s)e[s]=[],e[s][0]=n(t[0][s],t[1][s],t[2][s],t[3][s]),e[s][1]=[],e[s][1].push(...n(...e[s][0][0])),e[s][1].push(...n(...e[s][0][1])),e[s][2]=[],e[s][2].push(...n(...e[s][1][0])),e[s][2].push(...n(...e[s][1][1])),e[s][2].push(...n(...e[s][1][2])),e[s][2].push(...n(...e[s][1][3]));for(let t=0;t&lt;8;++t){s[t]=[];for(let r=0;r&lt;4;++r)s[t][r]=[],s[t][r][0]=n(e[0][2][t][r],e[1][2][t][r],e[2][2][t][r],e[3][2][t][r]),s[t][r][1]=[],s[t][r][1].push(...n(...s[t][r][0][0])),s[t][r][1].push(...n(...s[t][r][0][1])),s[t][r][2]=[],s[t][r][2].push(...n(...s[t][r][1][0])),s[t][r][2].push(...n(...s[t][r][1][1])),s[t][r][2].push(...n(...s[t][r][1][2])),s[t][r][2].push(...n(...s[t][r][1][3]))}for(let t=0;t&lt;8;++t){r[t]=[];for(let e=0;e&lt;8;++e)r[t][e]=[],r[t][e][0]=s[t][0][2][e],r[t][e][1]=s[t][1][2][e],r[t][e][2]=s[t][2][2][e],r[t][e][3]=s[t][3][2][e]}return r};class x{constructor(t,e){this.x=t||0,this.y=e||0}toString(){return`(x=${this.x}, y=${this.y})`}clone(){return new x(this.x,this.y)}add(t){return new x(this.x+t.x,this.y+t.y)}scale(t){return void 0===t.x?new x(this.x*t,this.y*t):new x(this.x*t.x,this.y*t.y)}distSquared(t){let e=this.x-t.x,s=this.y-t.y;return e*e+s*s}transform(t){let e=this.x*t.a+this.y*t.c+t.e,s=this.x*t.b+this.y*t.d+t.f;return new x(e,s)}}class g{constructor(t,e,s,r,n,o){void 0===t?(this.a=1,this.b=0,this.c=0,this.d=1,this.e=0,this.f=0):(this.a=t,this.b=e,this.c=s,this.d=r,this.e=n,this.f=o)}toString(){return`affine: ${this.a} ${this.c} ${this.e} \n       ${this.b} ${this.d} ${this.f}`}append(t){t instanceof g||console.error(&quot;mesh.js: argument to Affine.append is not affine!&quot;);let e=this.a*t.a+this.c*t.b,s=this.b*t.a+this.d*t.b,r=this.a*t.c+this.c*t.d,n=this.b*t.c+this.d*t.d,o=this.a*t.e+this.c*t.f+this.e,i=this.b*t.e+this.d*t.f+this.f;return new g(e,s,r,n,o,i)}}class w{constructor(t,e){this.nodes=t,this.colors=e}paintCurve(t,e){if(o(this.nodes)&gt;r){const s=n(...this.nodes);let r=[[],[]],o=[[],[]];for(let t=0;t&lt;4;++t)r[0][t]=this.colors[0][t],r[1][t]=(this.colors[0][t]+this.colors[1][t])/2,o[0][t]=r[1][t],o[1][t]=this.colors[1][t];let i=new w(s[0],r),a=new w(s[1],o);i.paintCurve(t,e),a.paintCurve(t,e)}else{let s=Math.round(this.nodes[0].x);if(s&gt;=0&amp;&amp;s&lt;e){let r=4*(~~this.nodes[0].y*e+s);t[r]=Math.round(this.colors[0][0]),t[r+1]=Math.round(this.colors[0][1]),t[r+2]=Math.round(this.colors[0][2]),t[r+3]=Math.round(this.colors[0][3])}}}}class m{constructor(t,e){this.nodes=t,this.colors=e}split(){let t=[[],[],[],[]],e=[[],[],[],[]],s=[[[],[]],[[],[]]],r=[[[],[]],[[],[]]];for(let s=0;s&lt;4;++s){const r=n(this.nodes[0][s],this.nodes[1][s],this.nodes[2][s],this.nodes[3][s]);t[0][s]=r[0][0],t[1][s]=r[0][1],t[2][s]=r[0][2],t[3][s]=r[0][3],e[0][s]=r[1][0],e[1][s]=r[1][1],e[2][s]=r[1][2],e[3][s]=r[1][3]}for(let t=0;t&lt;4;++t)s[0][0][t]=this.colors[0][0][t],s[0][1][t]=this.colors[0][1][t],s[1][0][t]=(this.colors[0][0][t]+this.colors[1][0][t])/2,s[1][1][t]=(this.colors[0][1][t]+this.colors[1][1][t])/2,r[0][0][t]=s[1][0][t],r[0][1][t]=s[1][1][t],r[1][0][t]=this.colors[1][0][t],r[1][1][t]=this.colors[1][1][t];return[new m(t,s),new m(e,r)]}paint(t,e){let s,n=!1;for(let t=0;t&lt;4;++t)if((s=o([this.nodes[0][t],this.nodes[1][t],this.nodes[2][t],this.nodes[3][t]]))&gt;r){n=!0;break}if(n){let s=this.split();s[0].paint(t,e),s[1].paint(t,e)}else{new w([...this.nodes[0]],[...this.colors[0]]).paintCurve(t,e)}}}class b{constructor(t){this.readMesh(t),this.type=t.getAttribute(&quot;type&quot;)||&quot;bilinear&quot;}readMesh(t){let e=[[]],s=[[]],r=Number(t.getAttribute(&quot;x&quot;)),n=Number(t.getAttribute(&quot;y&quot;));e[0][0]=new x(r,n);let o=t.children;for(let t=0,r=o.length;t&lt;r;++t){e[3*t+1]=[],e[3*t+2]=[],e[3*t+3]=[],s[t+1]=[];let r=o[t].children;for(let n=0,o=r.length;n&lt;o;++n){let o=r[n].children;for(let r=0,i=o.length;r&lt;i;++r){let i=r;0!==t&amp;&amp;++i;let h,d=o[r].getAttribute(&quot;path&quot;),c=&quot;l&quot;;null!=d&amp;&amp;(c=(h=d.match(/\s*([lLcC])\s*(.*)/))[1]);let u=l(h[2]);switch(c){case&quot;l&quot;:0===i?(e[3*t][3*n+3]=u[0].add(e[3*t][3*n]),e[3*t][3*n+1]=a(e[3*t][3*n],e[3*t][3*n+3]),e[3*t][3*n+2]=a(e[3*t][3*n+3],e[3*t][3*n])):1===i?(e[3*t+3][3*n+3]=u[0].add(e[3*t][3*n+3]),e[3*t+1][3*n+3]=a(e[3*t][3*n+3],e[3*t+3][3*n+3]),e[3*t+2][3*n+3]=a(e[3*t+3][3*n+3],e[3*t][3*n+3])):2===i?(0===n&amp;&amp;(e[3*t+3][3*n+0]=u[0].add(e[3*t+3][3*n+3])),e[3*t+3][3*n+1]=a(e[3*t+3][3*n],e[3*t+3][3*n+3]),e[3*t+3][3*n+2]=a(e[3*t+3][3*n+3],e[3*t+3][3*n])):(e[3*t+1][3*n]=a(e[3*t][3*n],e[3*t+3][3*n]),e[3*t+2][3*n]=a(e[3*t+3][3*n],e[3*t][3*n]));break;case&quot;L&quot;:0===i?(e[3*t][3*n+3]=u[0],e[3*t][3*n+1]=a(e[3*t][3*n],e[3*t][3*n+3]),e[3*t][3*n+2]=a(e[3*t][3*n+3],e[3*t][3*n])):1===i?(e[3*t+3][3*n+3]=u[0],e[3*t+1][3*n+3]=a(e[3*t][3*n+3],e[3*t+3][3*n+3]),e[3*t+2][3*n+3]=a(e[3*t+3][3*n+3],e[3*t][3*n+3])):2===i?(0===n&amp;&amp;(e[3*t+3][3*n+0]=u[0]),e[3*t+3][3*n+1]=a(e[3*t+3][3*n],e[3*t+3][3*n+3]),e[3*t+3][3*n+2]=a(e[3*t+3][3*n+3],e[3*t+3][3*n])):(e[3*t+1][3*n]=a(e[3*t][3*n],e[3*t+3][3*n]),e[3*t+2][3*n]=a(e[3*t+3][3*n],e[3*t][3*n]));break;case&quot;c&quot;:0===i?(e[3*t][3*n+1]=u[0].add(e[3*t][3*n]),e[3*t][3*n+2]=u[1].add(e[3*t][3*n]),e[3*t][3*n+3]=u[2].add(e[3*t][3*n])):1===i?(e[3*t+1][3*n+3]=u[0].add(e[3*t][3*n+3]),e[3*t+2][3*n+3]=u[1].add(e[3*t][3*n+3]),e[3*t+3][3*n+3]=u[2].add(e[3*t][3*n+3])):2===i?(e[3*t+3][3*n+2]=u[0].add(e[3*t+3][3*n+3]),e[3*t+3][3*n+1]=u[1].add(e[3*t+3][3*n+3]),0===n&amp;&amp;(e[3*t+3][3*n+0]=u[2].add(e[3*t+3][3*n+3]))):(e[3*t+2][3*n]=u[0].add(e[3*t+3][3*n]),e[3*t+1][3*n]=u[1].add(e[3*t+3][3*n]));break;case&quot;C&quot;:0===i?(e[3*t][3*n+1]=u[0],e[3*t][3*n+2]=u[1],e[3*t][3*n+3]=u[2]):1===i?(e[3*t+1][3*n+3]=u[0],e[3*t+2][3*n+3]=u[1],e[3*t+3][3*n+3]=u[2]):2===i?(e[3*t+3][3*n+2]=u[0],e[3*t+3][3*n+1]=u[1],0===n&amp;&amp;(e[3*t+3][3*n+0]=u[2])):(e[3*t+2][3*n]=u[0],e[3*t+1][3*n]=u[1]);break;default:console.error(&quot;mesh.js: &quot;+c+&quot; invalid path type.&quot;)}if(0===t&amp;&amp;0===n||r&gt;0){let e=window.getComputedStyle(o[r]).stopColor.match(/^rgb\s*\(\s*(\d+)\s*,\s*(\d+)\s*,\s*(\d+)\s*\)$/i),a=window.getComputedStyle(o[r]).stopOpacity,h=255;a&amp;&amp;(h=Math.floor(255*a)),e&amp;&amp;(0===i?(s[t][n]=[],s[t][n][0]=Math.floor(e[1]),s[t][n][1]=Math.floor(e[2]),s[t][n][2]=Math.floor(e[3]),s[t][n][3]=h):1===i?(s[t][n+1]=[],s[t][n+1][0]=Math.floor(e[1]),s[t][n+1][1]=Math.floor(e[2]),s[t][n+1][2]=Math.floor(e[3]),s[t][n+1][3]=h):2===i?(s[t+1][n+1]=[],s[t+1][n+1][0]=Math.floor(e[1]),s[t+1][n+1][1]=Math.floor(e[2]),s[t+1][n+1][2]=Math.floor(e[3]),s[t+1][n+1][3]=h):3===i&amp;&amp;(s[t+1][n]=[],s[t+1][n][0]=Math.floor(e[1]),s[t+1][n][1]=Math.floor(e[2]),s[t+1][n][2]=Math.floor(e[3]),s[t+1][n][3]=h))}}e[3*t+1][3*n+1]=new x,e[3*t+1][3*n+2]=new x,e[3*t+2][3*n+1]=new x,e[3*t+2][3*n+2]=new x,e[3*t+1][3*n+1].x=(-4*e[3*t][3*n].x+6*(e[3*t][3*n+1].x+e[3*t+1][3*n].x)+-2*(e[3*t][3*n+3].x+e[3*t+3][3*n].x)+3*(e[3*t+3][3*n+1].x+e[3*t+1][3*n+3].x)+-1*e[3*t+3][3*n+3].x)/9,e[3*t+1][3*n+2].x=(-4*e[3*t][3*n+3].x+6*(e[3*t][3*n+2].x+e[3*t+1][3*n+3].x)+-2*(e[3*t][3*n].x+e[3*t+3][3*n+3].x)+3*(e[3*t+3][3*n+2].x+e[3*t+1][3*n].x)+-1*e[3*t+3][3*n].x)/9,e[3*t+2][3*n+1].x=(-4*e[3*t+3][3*n].x+6*(e[3*t+3][3*n+1].x+e[3*t+2][3*n].x)+-2*(e[3*t+3][3*n+3].x+e[3*t][3*n].x)+3*(e[3*t][3*n+1].x+e[3*t+2][3*n+3].x)+-1*e[3*t][3*n+3].x)/9,e[3*t+2][3*n+2].x=(-4*e[3*t+3][3*n+3].x+6*(e[3*t+3][3*n+2].x+e[3*t+2][3*n+3].x)+-2*(e[3*t+3][3*n].x+e[3*t][3*n+3].x)+3*(e[3*t][3*n+2].x+e[3*t+2][3*n].x)+-1*e[3*t][3*n].x)/9,e[3*t+1][3*n+1].y=(-4*e[3*t][3*n].y+6*(e[3*t][3*n+1].y+e[3*t+1][3*n].y)+-2*(e[3*t][3*n+3].y+e[3*t+3][3*n].y)+3*(e[3*t+3][3*n+1].y+e[3*t+1][3*n+3].y)+-1*e[3*t+3][3*n+3].y)/9,e[3*t+1][3*n+2].y=(-4*e[3*t][3*n+3].y+6*(e[3*t][3*n+2].y+e[3*t+1][3*n+3].y)+-2*(e[3*t][3*n].y+e[3*t+3][3*n+3].y)+3*(e[3*t+3][3*n+2].y+e[3*t+1][3*n].y)+-1*e[3*t+3][3*n].y)/9,e[3*t+2][3*n+1].y=(-4*e[3*t+3][3*n].y+6*(e[3*t+3][3*n+1].y+e[3*t+2][3*n].y)+-2*(e[3*t+3][3*n+3].y+e[3*t][3*n].y)+3*(e[3*t][3*n+1].y+e[3*t+2][3*n+3].y)+-1*e[3*t][3*n+3].y)/9,e[3*t+2][3*n+2].y=(-4*e[3*t+3][3*n+3].y+6*(e[3*t+3][3*n+2].y+e[3*t+2][3*n+3].y)+-2*(e[3*t+3][3*n].y+e[3*t][3*n+3].y)+3*(e[3*t][3*n+2].y+e[3*t+2][3*n].y)+-1*e[3*t][3*n].y)/9}}this.nodes=e,this.colors=s}paintMesh(t,e){let s=(this.nodes.length-1)/3,r=(this.nodes[0].length-1)/3;if(&quot;bilinear&quot;===this.type||s&lt;2||r&lt;2){let n;for(let o=0;o&lt;s;++o)for(let s=0;s&lt;r;++s){let r=[];for(let t=3*o,e=3*o+4;t&lt;e;++t)r.push(this.nodes[t].slice(3*s,3*s+4));let i=[];i.push(this.colors[o].slice(s,s+2)),i.push(this.colors[o+1].slice(s,s+2)),(n=new m(r,i)).paint(t,e)}}else{let n,o,a,h,l,d,u;const x=s,g=r;s++,r++;let w=new Array(s);for(let t=0;t&lt;s;++t){w[t]=new Array(r);for(let e=0;e&lt;r;++e)w[t][e]=[],w[t][e][0]=this.nodes[3*t][3*e],w[t][e][1]=this.colors[t][e]}for(let t=0;t&lt;s;++t)for(let e=0;e&lt;r;++e)0!==t&amp;&amp;t!==x&amp;&amp;(n=i(w[t-1][e][0],w[t][e][0]),o=i(w[t+1][e][0],w[t][e][0]),w[t][e][2]=c(w[t-1][e][1],w[t][e][1],w[t+1][e][1],n,o)),0!==e&amp;&amp;e!==g&amp;&amp;(n=i(w[t][e-1][0],w[t][e][0]),o=i(w[t][e+1][0],w[t][e][0]),w[t][e][3]=c(w[t][e-1][1],w[t][e][1],w[t][e+1][1],n,o));for(let t=0;t&lt;r;++t){w[0][t][2]=[],w[x][t][2]=[];for(let e=0;e&lt;4;++e)n=i(w[1][t][0],w[0][t][0]),o=i(w[x][t][0],w[x-1][t][0]),w[0][t][2][e]=n&gt;0?2*(w[1][t][1][e]-w[0][t][1][e])/n-w[1][t][2][e]:0,w[x][t][2][e]=o&gt;0?2*(w[x][t][1][e]-w[x-1][t][1][e])/o-w[x-1][t][2][e]:0}for(let t=0;t&lt;s;++t){w[t][0][3]=[],w[t][g][3]=[];for(let e=0;e&lt;4;++e)n=i(w[t][1][0],w[t][0][0]),o=i(w[t][g][0],w[t][g-1][0]),w[t][0][3][e]=n&gt;0?2*(w[t][1][1][e]-w[t][0][1][e])/n-w[t][1][3][e]:0,w[t][g][3][e]=o&gt;0?2*(w[t][g][1][e]-w[t][g-1][1][e])/o-w[t][g-1][3][e]:0}for(let s=0;s&lt;x;++s)for(let r=0;r&lt;g;++r){let n=i(w[s][r][0],w[s+1][r][0]),o=i(w[s][r+1][0],w[s+1][r+1][0]),c=i(w[s][r][0],w[s][r+1][0]),x=i(w[s+1][r][0],w[s+1][r+1][0]),g=[[],[],[],[]];for(let t=0;t&lt;4;++t){(d=[])[0]=w[s][r][1][t],d[1]=w[s+1][r][1][t],d[2]=w[s][r+1][1][t],d[3]=w[s+1][r+1][1][t],d[4]=w[s][r][2][t]*n,d[5]=w[s+1][r][2][t]*n,d[6]=w[s][r+1][2][t]*o,d[7]=w[s+1][r+1][2][t]*o,d[8]=w[s][r][3][t]*c,d[9]=w[s+1][r][3][t]*x,d[10]=w[s][r+1][3][t]*c,d[11]=w[s+1][r+1][3][t]*x,d[12]=0,d[13]=0,d[14]=0,d[15]=0,u=f(d);for(let e=0;e&lt;9;++e){g[t][e]=[];for(let s=0;s&lt;9;++s)g[t][e][s]=p(u,e/8,s/8),g[t][e][s]&gt;255?g[t][e][s]=255:g[t][e][s]&lt;0&amp;&amp;(g[t][e][s]=0)}}h=[];for(let t=3*s,e=3*s+4;t&lt;e;++t)h.push(this.nodes[t].slice(3*r,3*r+4));l=y(h);for(let s=0;s&lt;8;++s)for(let r=0;r&lt;8;++r)(a=new m(l[s][r],[[[g[0][s][r],g[1][s][r],g[2][s][r],g[3][s][r]],[g[0][s][r+1],g[1][s][r+1],g[2][s][r+1],g[3][s][r+1]]],[[g[0][s+1][r],g[1][s+1][r],g[2][s+1][r],g[3][s+1][r]],[g[0][s+1][r+1],g[1][s+1][r+1],g[2][s+1][r+1],g[3][s+1][r+1]]]])).paint(t,e)}}}transform(t){if(t instanceof x)for(let e=0,s=this.nodes.length;e&lt;s;++e)for(let s=0,r=this.nodes[0].length;s&lt;r;++s)this.nodes[e][s]=this.nodes[e][s].add(t);else if(t instanceof g)for(let e=0,s=this.nodes.length;e&lt;s;++e)for(let s=0,r=this.nodes[0].length;s&lt;r;++s)this.nodes[e][s]=this.nodes[e][s].transform(t)}scale(t){for(let e=0,s=this.nodes.length;e&lt;s;++e)for(let s=0,r=this.nodes[0].length;s&lt;r;++s)this.nodes[e][s]=this.nodes[e][s].scale(t)}}document.querySelectorAll(&quot;rect,circle,ellipse,path,text&quot;).forEach((r,n)=&gt;{let o=r.getAttribute(&quot;id&quot;);o||(o=&quot;patchjs_shape&quot;+n,r.setAttribute(&quot;id&quot;,o));const i=r.style.fill.match(/^url\(\s*&quot;?\s*#([^\s&quot;]+)&quot;?\s*\)/),a=r.style.stroke.match(/^url\(\s*&quot;?\s*#([^\s&quot;]+)&quot;?\s*\)/);if(i&amp;&amp;i[1]){const a=document.getElementById(i[1]);if(a&amp;&amp;&quot;meshgradient&quot;===a.nodeName){const i=r.getBBox();let l=document.createElementNS(s,&quot;canvas&quot;);d(l,{width:i.width,height:i.height});const c=l.getContext(&quot;2d&quot;);let u=c.createImageData(i.width,i.height);const f=new b(a);&quot;objectBoundingBox&quot;===a.getAttribute(&quot;gradientUnits&quot;)&amp;&amp;f.scale(new x(i.width,i.height));const p=a.getAttribute(&quot;gradientTransform&quot;);null!=p&amp;&amp;f.transform(h(p)),&quot;userSpaceOnUse&quot;===a.getAttribute(&quot;gradientUnits&quot;)&amp;&amp;f.transform(new x(-i.x,-i.y)),f.paintMesh(u.data,l.width),c.putImageData(u,0,0);const y=document.createElementNS(t,&quot;image&quot;);d(y,{width:i.width,height:i.height,x:i.x,y:i.y});let g=l.toDataURL();y.setAttributeNS(e,&quot;xlink:href&quot;,g),r.parentNode.insertBefore(y,r),r.style.fill=&quot;none&quot;;const w=document.createElementNS(t,&quot;use&quot;);w.setAttributeNS(e,&quot;xlink:href&quot;,&quot;#&quot;+o);const m=&quot;patchjs_clip&quot;+n,M=document.createElementNS(t,&quot;clipPath&quot;);M.setAttribute(&quot;id&quot;,m),M.appendChild(w),r.parentElement.insertBefore(M,r),y.setAttribute(&quot;clip-path&quot;,&quot;url(#&quot;+m+&quot;)&quot;),u=null,l=null,g=null}}if(a&amp;&amp;a[1]){const o=document.getElementById(a[1]);if(o&amp;&amp;&quot;meshgradient&quot;===o.nodeName){const i=parseFloat(r.style.strokeWidth.slice(0,-2))*(parseFloat(r.style.strokeMiterlimit)||parseFloat(r.getAttribute(&quot;stroke-miterlimit&quot;))||1),a=r.getBBox(),l=Math.trunc(a.width+i),c=Math.trunc(a.height+i),u=Math.trunc(a.x-i/2),f=Math.trunc(a.y-i/2);let p=document.createElementNS(s,&quot;canvas&quot;);d(p,{width:l,height:c});const y=p.getContext(&quot;2d&quot;);let g=y.createImageData(l,c);const w=new b(o);&quot;objectBoundingBox&quot;===o.getAttribute(&quot;gradientUnits&quot;)&amp;&amp;w.scale(new x(l,c));const m=o.getAttribute(&quot;gradientTransform&quot;);null!=m&amp;&amp;w.transform(h(m)),&quot;userSpaceOnUse&quot;===o.getAttribute(&quot;gradientUnits&quot;)&amp;&amp;w.transform(new x(-u,-f)),w.paintMesh(g.data,p.width),y.putImageData(g,0,0);const M=document.createElementNS(t,&quot;image&quot;);d(M,{width:l,height:c,x:0,y:0});let S=p.toDataURL();M.setAttributeNS(e,&quot;xlink:href&quot;,S);const k=&quot;pattern_clip&quot;+n,A=document.createElementNS(t,&quot;pattern&quot;);d(A,{id:k,patternUnits:&quot;userSpaceOnUse&quot;,width:l,height:c,x:u,y:f}),A.appendChild(M),o.parentNode.appendChild(A),r.style.stroke=&quot;url(#&quot;+k+&quot;)&quot;,g=null,p=null,S=null}}})}();
                            </script>
                        </svg>
                        <span class="fs-5"></span>
                    </a>
                    <ul class="list-unstyled small">
                        <li class="mb-2">The best site to learn new skills;</li>
                        <li class="mb-2">Programming Languages ​​;</li>
                        <li class="mb-2">Early solutions in
                            the simplest</li>
                        <li class="mb-2"> ways New Poste with support from Bootstrap</li>
                    </ul>
                </div>
                <div class="col-6 col-lg-2 offset-lg-1 mb-3">
                    <h5>Links</h5>
                    <ul class="list-unstyled">
                        <li class="mb-2"><a href="/">Home</a></li>

                        <li class="mb-2"><a
                                href="https://www.new-poste.info/p/devlopement-tutorials-html-css.html">Learn HTML</a>
                        </li>
                        <li class="mb-2"><a href="https://www.new-poste.info/p/javascript-tutorials.html">Learn
                                JavaScript</a></li>
                        <li class="mb-2"><a href="https://www.new-poste.info/p/css-tutorials.html">Learn CSS</a></li>
                        <li class="mb-2"><a href="https://www.new-poste.info/p/react-tutorials.html">Learn React</a>
                        </li>
                        <li class="mb-2"><a href="https://www.new-poste.info/p/how-to-this.html" rel="noopener">How To
                                ?</a></li>
                    </ul>
                </div>
                <!--  <div class="col-6 col-lg-2 mb-3">
                    <h5>Guides</h5>
                    <ul class="list-unstyled">
                        <li class="mb-2"><a href="/docs/5.3/getting-started/">Getting started</a></li>
                        <li class="mb-2"><a href="/docs/5.3/examples/starter-template/">Starter template</a></li>
                        <li class="mb-2"><a href="/docs/5.3/getting-started/webpack/">Webpack</a></li>
                        <li class="mb-2"><a href="/docs/5.3/getting-started/parcel/">Parcel</a></li>
                        <li class="mb-2"><a href="/docs/5.3/getting-started/vite/">Vite</a></li>
                    </ul>
                </div>
           <div class="col-6 col-lg-2 mb-3">
                    <h5>Projects</h5>
                    <ul class="list-unstyled">
                        <li class="mb-2"><a href="https://github.com/twbs/bootstrap" 
                                rel="noopener">Bootstrap 5</a></li>
                        <li class="mb-2"><a href="https://github.com/twbs/bootstrap/tree/v4-dev" 
                                rel="noopener">Bootstrap 4</a></li>
                        <li class="mb-2"><a href="https://github.com/twbs/icons" 
                                rel="noopener">Icons</a></li>
                        <li class="mb-2"><a href="https://github.com/twbs/rfs"  rel="noopener">RFS</a>
                        </li>
                        <li class="mb-2"><a href="https://github.com/twbs/examples/" 
                                rel="noopener">Examples repo</a></li>
                    </ul>
                </div>-->
                <div class="col-6 col-lg-2 mb-3">
                    <h5>Community</h5>
                    <ul class="list-unstyled">
                        <li class="mb-2"><a href="https://github.com/twbs/bootstrap/issues" rel="noopener">Github</a>
                        </li>
                        <li class="mb-2"><a href="https://twitter.com/new_poste" rel="noopener">Twitter</a></li>

                        <li class="mb-2"><a href="https://opencollective.com/new-poste" rel="noopener">Open
                                Collective</a></li>
                        <li class="mb-2"><a href="https://www.new-poste.info/p/terms-and-conditions.html"
                                rel="noopener">TERMS AND CONDITIONS</a></li>
                        <li class="mb-2"><a href="https://www.new-poste.info/p/cookies-policy.html"
                                rel="noopener">COOKIES POLICY</a></li>
                    </ul>
                </div>
            </div>
        </div>
    </footer>

    <script src="https://getbootstrap.com/docs/5.3/dist/js/bootstrap.bundle.min.js"
        integrity="sha384-HwwvtgBNo3bZJJLYd8oVXjrBZt8cqVSpeBNS5n7C8IVInixGAoxmnlMuBnhbgrkm"
        crossorigin="anonymous"></script>


    <script src="https://cdn.jsdelivr.net/npm/@docsearch/js@3"></script>

    <script src="https://cdn.jsdelivr.net/npm/@stackblitz/sdk@1/bundles/sdk.umd.js"></script>

    <script src="https://getbootstrap.com/docs/5.3/assets/js/docs.min.js"></script>

    <script>

                document.querySelectorAll('.btn-edit').forEach(btn => {
                    btn.addEventListener('click', event => {
                        const htmlSnippet = event.target.closest('.bd-code-snippet').querySelector('.bd-example').innerHTML


                        const classes = Array.from(event.target.closest('.bd-code-snippet').querySelector('.bd-example').classList).join(' ')

                        const jsSnippet = event.target.closest('.bd-code-snippet').querySelector('.btn-edit').getAttribute('data-sb-js-snippet')
                        StackBlitzSDK.openBootstrapSnippet(htmlSnippet, jsSnippet, classes)
                    })
                })

                StackBlitzSDK.openBootstrapSnippet = (htmlSnippet, jsSnippet, classes) => {
                    const markup = `<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link href="https:\/\/cdn.jsdelivr.net\/npm\/bootstrap@5.3.1\/dist\/css\/bootstrap.min.css" rel="stylesheet">
    <link href="https://getbootstrap.com/docs/5.3/assets/css/docs.css" rel="stylesheet">
    <title>Bootstrap Example</title>
    <${'script'} src="https:\/\/cdn.jsdelivr.net\/npm\/bootstrap@5.3.1\/dist\/js\/bootstrap.bundle.min.js"></${'script'}>
  </head>
  <body class="p-3 m-0 border-0 ${classes}">

    <!-- Example Code -->
${htmlSnippet.replace(/^/gm, '    ')}
    <!-- End Example Code -->
  </body>
</html>`

                    const jsSnippetContent = jsSnippet ? '\/\/ NOTICE!!! Initially embedded in our docs this JavaScript\n\/\/ file contains elements that can help you create reproducible\n\/\/ use cases in StackBlitz for instance.\n\/\/ In a real project please adapt this content to your needs.\n\/\/ \u002b\u002b\u002b\u002b\u002b\u002b\u002b\u002b\u002b\u002b\u002b\u002b\u002b\u002b\u002b\u002b\u002b\u002b\u002b\u002b\u002b\u002b\u002b\u002b\u002b\u002b\u002b\u002b\u002b\u002b\u002b\u002b\u002b\u002b\u002b\u002b\u002b\u002b\u002b\u002b\u002b\u002b\n\n\/*!\n * JavaScript for Bootstrap\u0027s docs (https:\/\/getbootstrap.com\/)\n * Copyright 2011-2023 The Bootstrap Authors\n * Licensed under the Creative Commons Attribution 3.0 Unported License.\n * For details, see https:\/\/creativecommons.org\/licenses\/by\/3.0\/.\n *\/\n\n\/* global bootstrap: false *\/\n\n(() =\u003e {\n  \u0027use strict\u0027\n\n  \/\/ --------\n  \/\/ Tooltips\n  \/\/ --------\n  \/\/ Instantiate all tooltips in a docs or StackBlitz\n  document.querySelectorAll(\u0027[data-bs-toggle=\u0022tooltip\u0022]\u0027)\n    .forEach(tooltip =\u003e {\n      new bootstrap.Tooltip(tooltip)\n    })\n\n  \/\/ --------\n  \/\/ Popovers\n  \/\/ --------\n  \/\/ Instantiate all popovers in docs or StackBlitz\n  document.querySelectorAll(\u0027[data-bs-toggle=\u0022popover\u0022]\u0027)\n    .forEach(popover =\u003e {\n      new bootstrap.Popover(popover)\n    })\n\n  \/\/ -------------------------------\n  \/\/ Toasts\n  \/\/ -------------------------------\n  \/\/ Used by \u0027Placement\u0027 example in docs or StackBlitz\n  const toastPlacement = document.getElementById(\u0027toastPlacement\u0027)\n  if (toastPlacement) {\n    document.getElementById(\u0027selectToastPlacement\u0027).addEventListener(\u0027change\u0027, function () {\n      if (!toastPlacement.dataset.originalClass) {\n        toastPlacement.dataset.originalClass = toastPlacement.className\n      }\n\n      toastPlacement.className = \u0060${toastPlacement.dataset.originalClass} ${this.value}\u0060\n    })\n  }\n\n  \/\/ Instantiate all toasts in docs pages only\n  document.querySelectorAll(\u0027.bd-example .toast\u0027)\n    .forEach(toastNode =\u003e {\n      const toast = new bootstrap.Toast(toastNode, {\n        autohide: false\n      })\n\n      toast.show()\n    })\n\n  \/\/ Instantiate all toasts in docs pages only\n  \/\/ js-docs-start live-toast\n  const toastTrigger = document.getElementById(\u0027liveToastBtn\u0027)\n  const toastLiveExample = document.getElementById(\u0027liveToast\u0027)\n\n  if (toastTrigger) {\n    const toastBootstrap = bootstrap.Toast.getOrCreateInstance(toastLiveExample)\n    toastTrigger.addEventListener(\u0027click\u0027, () =\u003e {\n      toastBootstrap.show()\n    })\n  }\n  \/\/ js-docs-end live-toast\n\n  \/\/ -------------------------------\n  \/\/ Alerts\n  \/\/ -------------------------------\n  \/\/ Used in \u0027Show live alert\u0027 example in docs or StackBlitz\n\n  \/\/ js-docs-start live-alert\n  const alertPlaceholder = document.getElementById(\u0027liveAlertPlaceholder\u0027)\n  const appendAlert = (message, type) =\u003e {\n    const wrapper = document.createElement(\u0027div\u0027)\n    wrapper.innerHTML = [\n      \u0060\u003cdiv class=\u0022alert alert-${type} alert-dismissible\u0022 role=\u0022alert\u0022\u003e\u0060,\n      \u0060   \u003cdiv\u003e${message}\u003c\/div\u003e\u0060,\n      \u0027   \u003cbutton type=\u0022button\u0022 class=\u0022btn-close\u0022 data-bs-dismiss=\u0022alert\u0022 aria-label=\u0022Close\u0022\u003e\u003c\/button\u003e\u0027,\n      \u0027\u003c\/div\u003e\u0027\n    ].join(\u0027\u0027)\n\n    alertPlaceholder.append(wrapper)\n  }\n\n  const alertTrigger = document.getElementById(\u0027liveAlertBtn\u0027)\n  if (alertTrigger) {\n    alertTrigger.addEventListener(\u0027click\u0027, () =\u003e {\n      appendAlert(\u0027Nice, you triggered this alert message!\u0027, \u0027success\u0027)\n    })\n  }\n  \/\/ js-docs-end live-alert\n\n  \/\/ --------\n  \/\/ Carousels\n  \/\/ --------\n  \/\/ Instantiate all non-autoplaying carousels in docs or StackBlitz\n  document.querySelectorAll(\u0027.carousel:not([data-bs-ride=\u0022carousel\u0022])\u0027)\n    .forEach(carousel =\u003e {\n      bootstrap.Carousel.getOrCreateInstance(carousel)\n    })\n\n  \/\/ -------------------------------\n  \/\/ Checks \u0026 Radios\n  \/\/ -------------------------------\n  \/\/ Indeterminate checkbox example in docs and StackBlitz\n  document.querySelectorAll(\u0027.bd-example-indeterminate [type=\u0022checkbox\u0022]\u0027)\n    .forEach(checkbox =\u003e {\n      if (checkbox.id.includes(\u0027Indeterminate\u0027)) {\n        checkbox.indeterminate = true\n      }\n    })\n\n  \/\/ -------------------------------\n  \/\/ Links\n  \/\/ -------------------------------\n  \/\/ Disable empty links in docs examples only\n  document.querySelectorAll(\u0027.bd-content [href=\u0022#\u0022]\u0027)\n    .forEach(link =\u003e {\n      link.addEventListener(\u0027click\u0027, event =\u003e {\n        event.preventDefault()\n      })\n    })\n\n  \/\/ -------------------------------\n  \/\/ Modal\n  \/\/ -------------------------------\n  \/\/ Modal \u0027Varying modal content\u0027 example in docs and StackBlitz\n  \/\/ js-docs-start varying-modal-content\n  const exampleModal = document.getElementById(\u0027exampleModal\u0027)\n  if (exampleModal) {\n    exampleModal.addEventListener(\u0027show.bs.modal\u0027, event =\u003e {\n      \/\/ Button that triggered the modal\n      const button = event.relatedTarget\n      \/\/ Extract info from data-bs-* attributes\n      const recipient = button.getAttribute(\u0027data-bs-whatever\u0027)\n      \/\/ If necessary, you could initiate an Ajax request here\n      \/\/ and then do the updating in a callback.\n\n      \/\/ Update the modal\u0027s content.\n      const modalTitle = exampleModal.querySelector(\u0027.modal-title\u0027)\n      const modalBodyInput = exampleModal.querySelector(\u0027.modal-body input\u0027)\n\n      modalTitle.textContent = \u0060New message to ${recipient}\u0060\n      modalBodyInput.value = recipient\n    })\n  }\n  \/\/ js-docs-end varying-modal-content\n\n  \/\/ -------------------------------\n  \/\/ Offcanvas\n  \/\/ -------------------------------\n  \/\/ \u0027Offcanvas components\u0027 example in docs only\n  const myOffcanvas = document.querySelectorAll(\u0027.bd-example-offcanvas .offcanvas\u0027)\n  if (myOffcanvas) {\n    myOffcanvas.forEach(offcanvas =\u003e {\n      offcanvas.addEventListener(\u0027show.bs.offcanvas\u0027, event =\u003e {\n        event.preventDefault()\n      }, false)\n    })\n  }\n})()\n' : null
                    const project = {
                        files: {
                            'index.html': markup,
                            'index.js': jsSnippetContent
                        },
                        title: 'Bootstrap Example',
                        description: `Official example from ${window.location.href}`,
                        template: jsSnippet ? 'javascript' : 'html',
                        tags: ['bootstrap']
                    }

                    StackBlitzSDK.openProject(project, { openFile: 'index.html' })
                }
    </script>



    <div class="position-fixed" aria-hidden="true"><input type="text" tabindex="-1"></div>



</body>

</html>
