<template>
  <div class="page js_show uploader">
    <div class="page__hd">
      <h1 class="page__title">Uploader</h1>
      <p class="page__desc">上传组件，一般配合<a class="link" href="#gallery">组件Gallery</a>来使用。</p>
    </div>
    <div class="page__bd">
      <div class="weui-gallery" id="gallery">
        <span class="weui-gallery__img" id="galleryImg"></span>
        <div class="weui-gallery__opr">
          <a href="javascript:" class="weui-gallery__del">
            <i class="weui-icon-delete weui-icon_gallery-delete"></i>
          </a>
        </div>
      </div>

      <div class="weui-cells weui-cells_form">
        <div class="weui-cell">
          <div class="weui-cell__bd">
            <div class="weui-uploader">
              <div class="weui-uploader__hd">
                <p class="weui-uploader__title">图片上传</p>
                <div class="weui-uploader__info">0/2</div>
              </div>
              <div class="weui-uploader__bd">
                <ul class="weui-uploader__files" id="uploaderFiles">
                  <li class="weui-uploader__file" style="background-image:url(./images/pic_160.png)"></li>
                  <li class="weui-uploader__file" style="background-image:url(./images/pic_160.png)"></li>
                  <li class="weui-uploader__file" style="background-image:url(./images/pic_160.png)"></li>
                  <li class="weui-uploader__file weui-uploader__file_status" style="background-image:url(./images/pic_160.png)">
                    <div class="weui-uploader__file-content">
                      <i class="weui-icon-warn"></i>
                    </div>
                  </li>
                  <li class="weui-uploader__file weui-uploader__file_status" style="background-image:url(./images/pic_160.png)">
                    <div class="weui-uploader__file-content">50%</div>
                  </li>
                </ul>
                <div class="weui-uploader__input-box">
                  <input id="uploaderInput" class="weui-uploader__input" type="file" accept="image/*" multiple />
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="page__ft">
      <a href="javascript:home()"><img src="./images/icon_footer_link.png" /></a>
    </div>
  </div>
</template>

<script>
  export default {
    name: 'uploader',
    data() {
      return {};
    },
  };

</script>
