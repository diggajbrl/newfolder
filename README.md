*,
::after,
::before {
    box-sizing: border-box;
}

:root {
    --bs-gutter-x: 1.5rem;
    --bs-gutter-y: 0;
}

.container {
    width: 100%;
    padding-right: calc(var(--bs-gutter-x) * 0.5);
    padding-left: calc(var(--bs-gutter-x) * 0.5);
    margin-right: auto;
    margin-left: auto;
}

@media (min-width: 576px) {
    .container {
        max-width: 540px;
    }
}

@media (min-width: 768px) {
    .container {
        max-width: 720px;
    }
}

@media (min-width: 992px) {
    .container {
        max-width: 960px;
    }
}

@media (min-width: 1200px) {
    .container {
        max-width: 1140px;
    }
}

@media (min-width: 1400px) {
    .container {
        max-width: 1320px;
    }
}

.row {
    display: flex;
    flex-wrap: wrap;
    margin-top: calc(-1 * var(--bs-gutter-y));
    margin-right: calc(-0.5 * var(--bs-gutter-x));
    margin-left: calc(-0.5 * var(--bs-gutter-x));
}

.row>* {
    flex-shrink: 0;
    width: 100%;
    max-width: 100%;
    padding-right: calc(var(--bs-gutter-x) * 0.5);
    padding-left: calc(var(--bs-gutter-x) * 0.5);
    margin-top: var(--bs-gutter-y);
}

[class^="col-lg-"] {
    width: 100%;
}

@media (min-width: 992px) {
    .col-lg-1 {
        flex: 0 0 auto;
        width: 8.33333333%;
    }

    .col-lg-2 {
        flex: 0 0 auto;
        width: 16.66666667%;
    }

    .col-lg-3 {
        flex: 0 0 auto;
        width: 25%;
    }

    .col-lg-4 {
        flex: 0 0 auto;
        width: 33.33333333%;
    }

    .col-lg-5 {
        flex: 0 0 auto;
        width: 41.66666667%;
    }

    .col-lg-6 {
        flex: 0 0 auto;
        width: 50%;
    }

    .col-lg-7 {
        flex: 0 0 auto;
        width: 58.33333333%;
    }

    .col-lg-8 {
        flex: 0 0 auto;
        width: 66.66666667%;
    }

    .col-lg-9 {
        flex: 0 0 auto;
        width: 75%;
    }

    .col-lg-10 {
        flex: 0 0 auto;
        width: 83.33333333%;
    }

    .col-lg-11 {
        flex: 0 0 auto;
        width: 91.66666667%;
    }

    .col-lg-12 {
        flex: 0 0 auto;
        width: 100%;
    }
}
