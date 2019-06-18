# toast_diy_width_height
自定义Toast，设置toast的宽高

      View view = LayoutInflater.from(FaceActivity.this).inflate(R.layout.toast_failed, null);
        LinearLayout linear = (LinearLayout) view.findViewById(R.id.toast_linear);
        int width = ((int) getResources().getDimension(R.dimen.x100));
        RelativeLayout.LayoutParams layoutParams = new RelativeLayout.LayoutParams(width,width);
        linear.setLayoutParams(layoutParams);
