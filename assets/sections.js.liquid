/*============================================================================
  Slideshow
==============================================================================*/

window.slideshow = {
  init() {
    $('.js-homepage-slideshow').each(function () {
      const $homepageSlider = $(this);
      const settings = {
        slideshowSpeed: $homepageSlider.data('slideshow-speed') * 1000,
        slideshowTextAnimation: $homepageSlider.data('slideshow-text-animation'),
        adaptiveHeight: $homepageSlider.data('adaptive-height'),
      };

      // Initiate the slideshow
      if (!$homepageSlider.hasClass('flickity-enabled')) {
        const arrowShow = $homepageSlider.find('.gallery-cell').length === 1 ? false : true;
        $homepageSlider.flickity({
          adaptiveHeight: settings.adaptiveHeight,
          wrapAround: true,
          cellAlign: 'left',
          imagesLoaded: true,
          prevNextButtons: arrowShow,
          draggable: arrowShow,
          autoPlay: settings.slideshowSpeed,
        });

        if (settings.slideshowTextAnimation !== '') {
          const flkty = $homepageSlider.data('flickity');
          setTimeout(() => {
            $homepageSlider.find('.gallery-cell:nth-child(1) .caption-content').addClass(`animated ${settings.slideshowTextAnimation}`);
          }, 400);

          $homepageSlider.on('select.flickity', () => {
            if ($homepageSlider.is(':visible')) {
              const currentSlide = flkty.selectedIndex + 1;
              setTimeout(() => {
                $homepageSlider.find('.caption-content').removeClass(`animated ${settings.slideshowTextAnimation}`);
                $homepageSlider.find(`.gallery-cell:nth-child(${currentSlide}) .caption-content`).addClass(`animated ${settings.slideshowTextAnimation}`);
              }, 400);
            }
          });
        }
      }

      if ($homepageSlider.find('.gallery-cell').length > 1) {
        $homepageSlider.addClass('multi-image');
      } else {
        $homepageSlider.addClass('single-image');
      }
    });
  },
  unload($target) {
    const $slider = $target.find('.js-homepage-slideshow');
    $slider.flickity('destroy');
  },
};