<template>
    <div class="footer">
        <div class="container">
            <a href="#"  class="logo">
                <svg width="110" height="50" viewBox="0 0 110 50" fill="none" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
                    <rect width="110" height="50" fill="url(#pattern0)"/>
                    <defs>
                    <pattern id="pattern0" patternContentUnits="objectBoundingBox" width="1" height="1">
                    <use xlink:href="#image0" transform="translate(0 -0.00416667) scale(0.00595238 0.0130952)"/>
                    </pattern>
                    <image id="image0" width="168" height="77" xlink:href="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAKgAAABNCAYAAAAywi+FAAAAGXRFWHRTb2Z0d2FyZQBBZG9iZSBJbWFnZVJlYWR5ccllPAAAA+tpVFh0WE1MOmNvbS5hZG9iZS54bXAAAAAAADw/eHBhY2tldCBiZWdpbj0i77u/IiBpZD0iVzVNME1wQ2VoaUh6cmVTek5UY3prYzlkIj8+IDx4OnhtcG1ldGEgeG1sbnM6eD0iYWRvYmU6bnM6bWV0YS8iIHg6eG1wdGs9IkFkb2JlIFhNUCBDb3JlIDUuNi1jMTExIDc5LjE1ODMyNSwgMjAxNS8wOS8xMC0wMToxMDoyMCAgICAgICAgIj4gPHJkZjpSREYgeG1sbnM6cmRmPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5LzAyLzIyLXJkZi1zeW50YXgtbnMjIj4gPHJkZjpEZXNjcmlwdGlvbiByZGY6YWJvdXQ9IiIgeG1sbnM6eG1wPSJodHRwOi8vbnMuYWRvYmUuY29tL3hhcC8xLjAvIiB4bWxuczpkYz0iaHR0cDovL3B1cmwub3JnL2RjL2VsZW1lbnRzLzEuMS8iIHhtbG5zOnhtcE1NPSJodHRwOi8vbnMuYWRvYmUuY29tL3hhcC8xLjAvbW0vIiB4bWxuczpzdFJlZj0iaHR0cDovL25zLmFkb2JlLmNvbS94YXAvMS4wL3NUeXBlL1Jlc291cmNlUmVmIyIgeG1wOkNyZWF0b3JUb29sPSJBZG9iZSBQaG90b3Nob3AgQ0MgMjAxNSAoV2luZG93cykiIHhtcDpDcmVhdGVEYXRlPSIyMDIxLTA3LTE0VDE3OjI4OjIwKzA1OjAwIiB4bXA6TW9kaWZ5RGF0ZT0iMjAyMS0wNy0xNFQxNzoyODoyNCswNTowMCIgeG1wOk1ldGFkYXRhRGF0ZT0iMjAyMS0wNy0xNFQxNzoyODoyNCswNTowMCIgZGM6Zm9ybWF0PSJpbWFnZS9wbmciIHhtcE1NOkluc3RhbmNlSUQ9InhtcC5paWQ6RkI5OTZCQ0ZFNDlFMTFFQjkwN0FCNjg3MzQ4MTQ0NzgiIHhtcE1NOkRvY3VtZW50SUQ9InhtcC5kaWQ6RkI5OTZCRDBFNDlFMTFFQjkwN0FCNjg3MzQ4MTQ0NzgiPiA8eG1wTU06RGVyaXZlZEZyb20gc3RS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"/>
                    </defs>
                </svg>
            </a>
            <div class="row">
                <div class="col-4 offset-lg-0 offset-4">
                    <p class="footer__text">
                        Все права защищены.<br>Traffic Shark @ 2015-2021
                    </p>
                    <a href="#" class="footer__link">
                        Terms & Conditions
                    </a>
                    <a href="#" class="footer__link">
                        Privacy police
                    </a>
                </div>
                <div class="col-lg-2 col-4 offset-lg-1 offset-4">
                    <div class="footer-nav">
                        <a href="#" class="footer-nav__link d-flex align-items-center">
                            <svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
                                <g clip-path="url(#clip0)">
                                <path d="M12.5601 8.00004C12.5601 8.2868 12.4507 8.57351 12.2321 8.79214L5.35243 15.6718C4.9148 16.1094 4.20525 16.1094 3.76779 15.6718C3.33033 15.2343 3.33033 14.5249 3.76779 14.0872L9.85534 8.00004L3.768 1.91282C3.33054 1.47518 3.33054 0.765844 3.768 0.328423C4.20546 -0.109425 4.91501 -0.109425 5.35264 0.328422L12.2324 7.20795C12.4509 7.42668 12.5601 7.7134 12.5601 8.00004Z" fill="#2E9ADB"/>
                                </g>
                                <defs>
                                <clipPath id="clip0">
                                <rect width="16" height="16" fill="white" transform="translate(16) rotate(90)"/>
                                </clipPath>
                                </defs>
                            </svg>
                            Веб-мастерам
                        </a>
                        <a href="#" class="footer-nav__link d-flex align-items-center">
                            <svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
                                <g clip-path="url(#clip0)">
                                <path d="M12.5601 8.00004C12.5601 8.2868 12.4507 8.57351 12.2321 8.79214L5.35243 15.6718C4.9148 16.1094 4.20525 16.1094 3.76779 15.6718C3.33033 15.2343 3.33033 14.5249 3.76779 14.0872L9.85534 8.00004L3.768 1.91282C3.33054 1.47518 3.33054 0.765844 3.768 0.328423C4.20546 -0.109425 4.91501 -0.109425 5.35264 0.328422L12.2324 7.20795C12.4509 7.42668 12.5601 7.7134 12.5601 8.00004Z" fill="#2E9ADB"/>
                                </g>
                                <defs>
                                <clipPath id="clip0">
                                <rect width="16" height="16" fill="white" transform="translate(16) rotate(90)"/>
                                </clipPath>
                                </defs>
                            </svg>
                            Рекламодателям
                        </a>
                    </div>
                </div>
                <div class="col-lg-3 col-4 offset-lg-2 offset-4">
                    <div class="footer-social">
                        <a href="mail.com" class="footer-social__link d-flex align-items-center">
                            <svg class="social__icon" width="19" height="19" viewBox="0 0 19 19" fill="none" xmlns="http://www.w3.org/2000/svg">
                                <path d="M10.0496 11.9002C9.87013 12.0124 9.66824 12.0573 9.48878 12.0573C9.30933 12.0573 9.10744 12.0124 8.92798 11.9002L0 6.44922V13.6948C0 15.2426 1.2562 16.4988 2.80401 16.4988H16.196C17.7438 16.4988 19 15.2426 19 13.6948V6.44922L10.0496 11.9002Z" fill="#2E9ADB"/>
                                <path d="M16.1961 2.50122H2.80413C1.48063 2.50122 0.359029 3.44337 0.0898438 4.69956L9.51133 10.4422L18.9104 4.69956C18.6412 3.44337 17.5196 2.50122 16.1961 2.50122Z" fill="#2E9ADB"/>
                            </svg>
                            partner@trafficshark.pro
                        </a>
                        <a href="telegram.com" class="footer-social__link d-flex align-items-center">
                            <svg width="19" height="19" viewBox="0 0 19 19" fill="none" xmlns="http://www.w3.org/2000/svg">
                                <g clip-path="url(#clip0)">
                                <path d="M7.45502 12.0183L7.14073 16.439C7.5904 16.439 7.78515 16.2458 8.01869 16.0138L10.1269 13.999L14.4953 17.1982C15.2965 17.6447 15.8609 17.4095 16.0771 16.4611L18.9445 3.02495L18.9453 3.02416C19.1994 1.83983 18.517 1.3767 17.7364 1.66725L0.881813 8.12012C-0.268478 8.56662 -0.251062 9.20787 0.686272 9.49841L4.99531 10.8387L15.0044 4.57583C15.4754 4.26391 15.9037 4.4365 15.5514 4.74841L7.45502 12.0183Z" fill="#2E9ADB"/>
                                </g>
                                <defs>
                                <clipPath id="clip0">
                                <rect width="19" height="19" fill="white"/>
                                </clipPath>
                                </defs>
                            </svg>
                            @telegramname
                        </a>
                        <a href="skype.com" class="footer-social__link d-flex align-items-center">
                            <svg width="19" height="19" viewBox="0 0 19 19" fill="none" xmlns="http://www.w3.org/2000/svg">
                                <path d="M18.2085 9.49971C18.2085 8.32068 17.9795 7.19292 17.5219 6.11677C17.0643 5.04061 16.4458 4.11301 15.6665 3.33354C14.8872 2.55408 13.9595 1.93574 12.8833 1.47813C11.8071 1.02053 10.6794 0.791598 9.50014 0.791598C8.89804 0.791598 8.27953 0.857881 7.64473 0.989773C6.78685 0.330276 5.82202 0.000244141 4.75018 0.000244141C3.439 0.000244141 2.31953 0.46415 1.39172 1.39175C0.463906 2.31935 0 3.43861 0 4.75C0 5.82226 0.329607 6.78709 0.989529 7.64434C0.857424 8.27977 0.791566 8.89832 0.791566 9.49975C0.791566 10.6792 1.02049 11.8069 1.47814 12.8831C1.93574 13.9592 2.55429 14.8868 3.33355 15.6663C4.1128 16.4457 5.04061 17.0641 6.11677 17.5217C7.19293 17.9794 8.32065 18.2083 9.49989 18.2083C10.1018 18.2083 10.7203 18.142 11.3553 18.0101C12.213 18.6695 13.1778 18.9996 14.2499 18.9996C15.5611 18.9996 16.6805 18.5357 17.6083 17.6081C18.5362 16.6803 19 15.5608 19 14.2499C19 13.1776 18.6702 12.2132 18.0105 11.3551C18.1424 10.7208 18.2085 10.1022 18.2085 9.49971ZM14.1017 13.1923C13.8295 13.6747 13.4646 14.0606 13.0069 14.3491C12.5493 14.6376 12.044 14.8585 11.4915 15.0105C10.9389 15.1632 10.3616 15.2397 9.75975 15.2397C8.36609 15.2397 7.16607 14.9696 6.16005 14.4292C5.15385 13.8891 4.65095 13.2396 4.65095 12.4809C4.65095 12.1099 4.75598 11.8006 4.96651 11.5531C5.17678 11.3058 5.48781 11.1821 5.90037 11.1821C6.13949 11.1821 6.36212 11.2484 6.56829 11.3803C6.77425 11.5122 6.96421 11.6707 7.13726 11.8563C7.31052 12.0419 7.49783 12.2275 7.70015 12.413C7.90222 12.5985 8.17011 12.7575 8.50431 12.8894C8.83827 13.0213 9.21555 13.0871 9.63614 13.0871C10.172 13.0871 10.6051 12.9823 10.9349 12.772C11.2645 12.5613 11.4298 12.2956 11.4298 11.9737C11.4298 11.6441 11.2977 11.3967 11.0339 11.2315C10.8524 11.1165 10.3907 10.9682 9.64849 10.7864L7.84244 10.3409C7.34757 10.226 6.92284 10.0917 6.56832 9.93899C6.21359 9.78671 5.88374 9.58684 5.57879 9.3393C5.27364 9.09197 5.04277 8.78073 4.88617 8.40519C4.72937 8.03028 4.6512 7.59108 4.6512 7.08754C4.6512 6.4859 4.78914 5.95593 5.06552 5.49832C5.34166 5.04068 5.70874 4.68159 6.16638 4.42216C6.62402 4.16227 7.1167 3.96841 7.64452 3.84045C8.17209 3.71291 8.71636 3.64899 9.2773 3.64899C10.0689 3.64899 10.8193 3.74362 11.5286 3.93313C12.2377 4.12306 12.8233 4.40135 13.285 4.76804C13.7468 5.13534 13.9777 5.54556 13.9777 5.99928C13.9777 6.37029 13.8601 6.68779 13.6251 6.95158C13.3901 7.21536 13.0786 7.34725 12.6911 7.34725C12.4767 7.34725 12.2788 7.29789 12.0976 7.1989C11.9161 7.09992 11.7512 6.9806 11.6027 6.83982C11.4543 6.70014 11.2976 6.56153 11.1327 6.42571C10.9677 6.2895 10.745 6.17208 10.4648 6.07292C10.1843 5.97394 9.86683 5.92457 9.51228 5.92457C8.32479 5.92457 7.73115 6.2425 7.73115 6.87687C7.73115 7.01743 7.76211 7.14108 7.82387 7.24785C7.8858 7.35571 7.95381 7.44213 8.02788 7.50774C8.10216 7.57402 8.22584 7.63963 8.39886 7.70545C8.57212 7.77174 8.71615 7.81958 8.8318 7.84796C8.94723 7.87698 9.12874 7.91987 9.37603 7.97791L10.6625 8.2746C11.0664 8.36534 11.4272 8.46022 11.7449 8.5592C12.0623 8.65818 12.4025 8.79832 12.7655 8.97958C13.1283 9.16129 13.4293 9.36315 13.6686 9.58599C13.9077 9.80819 14.1076 10.0908 14.2685 10.433C14.4294 10.7757 14.5098 11.153 14.5098 11.5651C14.51 12.168 14.3738 12.71 14.1017 13.1923Z" fill="#2E9ADB"/>
                            </svg>
                            @skypename
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
    .footer{
        .logo{
            display: inline-block;
            margin-bottom: 30px;
        }
        padding: 70px 0 60px;
        &__text{
            font-family: Gilroy;
            font-style: normal;
            font-weight: 500;
            font-size: 16px;
            line-height: 19px;
            color: #7E7E7E;
            margin-bottom: 30px ;
        }
        &__link{
            font-family: Gilroy;
            font-style: normal;
            font-weight: bold;
            font-size: 14px;
            line-height: 17px;
            text-transform: uppercase;
            color: #2E9ADB;
            display: inline-block;
            &:not(:last-child){
                margin-bottom: 20px;
            }
        }
        &-nav{
            &__link{
                font-family: Gilroy;
                font-style: normal;
                font-weight: 500;
                font-size: 16px;
                line-height: 19px;
                color: #1C1C1C;
                svg{
                    margin-right: 10px;
                }
                &:first-child{
                    margin-bottom: 30px;
                }
            }
        }
        &-social{
            &__link{
                font-family: Gilroy;
                font-style: normal;
                font-weight: 500;
                font-size: 16px;
                line-height: 19px;
                color: #000000;
                &:not(:last-child){
                    margin-bottom: 30px;
                }
                svg{
                    margin-right: 10px;
                }
            }
        }
    }

    @media screen and (max-width: 992px){
        .footer{
            text-align: center;
            &__text{
                margin-bottom: 30px;
            }
            &__link{
                margin-bottom: 10px;
            }
            &-nav{
                margin-bottom: 30px;
            }
        }
    }
</style>